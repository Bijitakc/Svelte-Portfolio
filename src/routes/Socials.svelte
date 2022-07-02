<script>
    import github from '../assets/git.png'
    import gmail from '../assets/gmail.png'
    import linkedin from '../assets/li.png'
    import instagram from '../assets/in.jpg'
    import facebook from '../assets/f.png'
</script>

<div class="socials">
    <a href="">
        <span>
            <img src={gmail} alt="Gmail">
        </span>
    </a>
    <a href="">
        <span>
            <img src={linkedin} alt="Linkedin">
        </span>
    </a>
    <a href="">
        <span>
            <img src={github} alt="Github">
        </span>
    </a>
    <a href="">
        <span>
            <img src={instagram} alt="Instagram">
        </span>
    </a>
    <a href="">
        <span>
            <img src={facebook} alt="Facebook">
        </span>
    </a>
</div>

<style>
    .socials {
        display: flex;
        gap: 10px;
        background-color: white;
        float: right;
    }
    .socials span {
        padding: 0px;
        border: none;
    }
    .socials a{
        background-color: none;
        margin: none;
    }
    .socials img {
        height: 40px;
        width: 40px;
    }
</style>