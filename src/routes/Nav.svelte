<script>
    import logo from '../assets/logobl.png'
    import skills from '../assets/skills.png'
    import pf from '../assets/portfolio.png'
    import contact from '../assets/contact.png'
</script>

<div class="navbar">
    <div class="nav-item">
        <a href="/">
            <button>
                <img class="logo-img logo" src={logo} alt="Logo" >
                <p class="nav-text home">Home</p>
            </button>
        </a>
    </div>
    <!-- <div class="nav-item">
        <a href="">
            <button>
                <img class="logo-img skills" src={skills} alt="Skills logo" >
                <p class="nav-text">Skills</p>
            </button>
        </a>
    </div> -->
    <div class="nav-item">
        <a href="/#/projects">
            <button>
                <img class="logo-img pf" src={pf} alt="Portfolio logo" >
                <p class="nav-text" >Projects</p>
            </button>
        </a>
    </div>
    <!-- <div class="nav-item">
        <a href="">
            <button>
                <img class="logo-img contact" src={contact} alt="Contact logo" >
                <p class="nav-text" >Contact</p>
            </button>
        </a>
    </div> -->
</div>

<style>
    .navbar {
        position: fixed;
        background-color: white;
        display: flex;
        flex-direction: column;
        height: 100%;
        width: 70px;
        border: 1px rgba(0, 0, 0, 0.47);
    }
    .navbar button{
        border: none;
        cursor: pointer;
        background-color: inherit;
    }
    .nav-item {
        height: auto;
    }
    .nav-item:hover {
        background-color: grey;
    }
    .nav-text{
        font-family: 'Josefin Slab', serif;
    }
    .logo-img {
        background-color: inherit;
    }
    .logo {
        height: 74px;
        width: 55px;
    }
    .skills {
        height: 50px;
        width: 57px;
    }
    .pf {
        height: 60px;
        width: 51px;
    }
    .contact {
        height: 51px;
        width: 51px;
    }
</style>