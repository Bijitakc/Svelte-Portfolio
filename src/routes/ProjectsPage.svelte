<script>
    
</script>

<div class="projects-container">
    <div class="projects-list">
        <div class="project-showcase">
            <div class="project"></div>
            <p class="title">AppleBees Project</p>
        </div>
        <div class="project-showcase">
            <div class="project"></div>
            <p class="title">AppleBees Project</p>
        </div>
        <div class="project-showcase">
            <div class="project"></div>
            <p class="title">AppleBees Project</p>
        </div>
        <div class="project-showcase">
            <div class="project"></div>
            <p class="title">AppleBees Project</p>
        </div>
        <div class="project-showcase">
            <div class="project"></div>
            <p class="title">AppleBees Project</p>
        </div>
        <div class="project-showcase">
            <div class="project"></div>
            <p class="title">AppleBees Project</p>
        </div>
    </div>
</div>

<style>
    .projects-container {
        float: right;
        height: 676px;
        width: calc(100% - 100px);
        margin-top: 40px;
        box-sizing: border-box;
    }
    .projects-list {
        display: grid;
        grid-template-columns: auto auto auto;
        gap: 20px;
        margin: 0px 30px;
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
</style>