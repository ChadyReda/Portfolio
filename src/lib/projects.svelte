<script>

</script>

<section class="project-page">
    <div class="project-heading">
        My Projects
    </div>
    <div class="projects-container">
        <div class="project">
            <div class="project-title">
                Reda.io
            </div>
            <div class="project-description">
                Personal portfolio website, that respects the design and colors rules to provide a better user experience.
            </div>
            <div class="project-tech">
                <i class="fa-brands fa-js" ></i>
                <i class="fa-brands fa-html5" ></i>
                <i class="fa-brands fa-css3-alt" ></i>
                <i class="fa-brands fa-node-js" ></i>
            </div>
        </div>
    </div>
    <div class="seperator"></div>
</section>

<style>
    .project-page{
        width: 100%;
        height: fit-content;
    }
    .project-heading{
        color: white;
        font-size: 35px;
        font-family: 'Microsoft Sans Serif', sans-serif;
        margin-bottom: 40px;
    }
    .projects-container{
        width: 100%;
        display: flex;
        flex-wrap: wrap;
        column-gap: 50px;
        row-gap: 50px;
    }
    .project{
        background-color:rgba(31, 31, 31, 1);
        cursor: pointer;
        padding: 30px;
        height: 300px;
        min-width: 250px;
        max-width: 300px;
        gap: 20px;
        flex: 1;
        border-radius: 10px;
        display: grid;
        row-gap: 20px;
        font-family: 'Microsoft Sans Serif', sans-serif;
        grid-template-rows: 15% 50% 15%;
        box-shadow: 0 5px 5px rgb(7, 7, 7)
    }
    .project:hover{
        background: #0f0f0f;
        opacity: .9;
    }
    .project-title{
        display: flex;
        color: white;
        align-items: center;
        font-size: 30px;

    }
    .project-description{
        color: rgba(179, 179, 179, 1);
        line-height: 35px;
        font-size: 1rem;
        padding-top: 10px;
        display: flex;
        text-align: left;
    }
    .project-tech{
        display: flex;
        align-items: center;
    }
    .project-tech i{
        font-size: 2.5rem;
        color: grey;
        margin: 0 1.5rem 0 0;
    }
    .seperator{
        height: 1px;
        width: 100%;
        background-color: rgba(72, 72, 72, 1);
        margin: 40px 0 40px 0;
    }

</style>