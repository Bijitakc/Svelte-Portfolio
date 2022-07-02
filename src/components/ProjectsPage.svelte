<script>
    
</script>

<div class="projects-container">
    <h1> Project Showcase</h1>
    <div class="projects-list">
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
        height: 100%;
        width: 100%;
        text-align: center;
    }
    .projects-container h1 {
        margin-bottom: 40px;
    }
    .projects-list {
        display: flex;
        flex-direction: row;
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