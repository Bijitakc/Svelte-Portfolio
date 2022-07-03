<script>
    import github from '../assets/git.png'
</script>

<div class="projects-container">
    <div class="projects-list">
        <div class="project-showcase">
            <div class="project"></div>
            <p class="title">Asky</p>
        </div>
        <div class="project-showcase">
            <div class="project"></div>
            <p class="title">Unravel</p>
        </div>
        <div class="project-showcase">
            <div class="project"></div>
            <p class="title">Memegram</p>
        </div>
        <div class="project-showcase">
            <div class="project"></div>
            <p class="title">Bookworm</p>
        </div>
        <div class="project-showcase">
            <div class="project"></div>
            <p class="title">Bookworm</p>
        </div>
    </div>
    <div class="view-more">
        <span>
            <a href="">
                View more on Github
            </a>
        </span>
    </div>
</div>

<style>
    .projects-container {
        float: right;
        width: calc(100% - 100px);
        margin-top: 40px;
        box-sizing: border-box;
    }
    .projects-list {
        max-width: calc(100% - 100px);
        display: grid;
        gap: 15px;
        margin: 0px 10px;
    }
    .project-showcase {
        height: 260px;
        width: 260px;
        background-color: white;
        text-align: center;
        cursor: pointer;
    }
    .project-showcase:hover {
        opacity: 0.5;
    }
    .project {
        height: 200px;
        width: 260px;
        background-color: black;
    }
    .view-more {
        display: flex;
        justify-content: center;
        align-items: center;
        margin: 40px 10px 0 calc(40% - 70px);
        height: 40px;
        width: 321px;
        background-color: black; 
    }
    .view-more:hover, .view-more a:hover{
        background-color: yellow;
        color: black;
    }
    .view-more a{
        text-decoration: none;
        font-size: medium;
        color: white;
    }
    @media (min-width: 550px) {
        .projects-list {
            grid-template-columns: repeat(2, 1fr);
        }
    }
    @media (min-width: 800px) {
        .projects-list {
            grid-template-columns: repeat(3, 1fr);
        }
    }
    @media (min-width: 1060px) {
        .projects-list {
            grid-template-columns: repeat(4, 1fr);
        }
    }
    @media (min-width: 1280px) {
        .projects-list {
            grid-template-columns: repeat(5, 1fr);
        }
    }
</style>