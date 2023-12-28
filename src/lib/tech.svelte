<script>

</script>

<section class="techs">
    <div class="techHeading">
        My Tech
    </div>
    <div class="tech-container">
        <div class="tech">
            <div class="tech-title">
                JavaScript
            </div>  
            <div class="tech-desc">
                <i class="fa-brands fa-js" style="color: #737373;"></i>
            </div>
        </div>
        <div class="tech">
            <div class="tech-title">
                Figma
            </div>  
            <div class="tech-desc">
                <i class="fa-brands fa-figma" style="color: #737373;"></i>
            </div>
        </div>
        <div class="tech">
            <div class="tech-title">
                React
            </div>  
            <div class="tech-desc">
                <i class="fa-brands fa-react" style="color: #737373;"></i>
            </div>
        </div>
        <div class="tech">
            <div class="tech-title">
                Node-js
            </div>  
            <div class="tech-desc">
                <i class="fa-brands fa-node-js" style="color: #737373;"></i>
            </div>
        </div>
        <div class="tech">
            <div class="tech-title">
                Css
            </div>  
            <div class="tech-desc">
                <i class="fa-brands fa-css3-alt" style="color: #737373;"></i>
            </div>
        </div>
        <div class="tech">
            <div class="tech-title">
                Python
            </div>  
            <div class="tech-desc">
                <i class="fa-brands fa-python" style="color: #737373;"></i>
            </div>
        </div>
        <div class="tech">
            <div class="tech-title">
                Git
            </div>  
            <div class="tech-desc">
                <i class="fa-brands fa-git-alt" style="color: #737373;"></i>
            </div>
        </div>
        <div class="tech">
            <div class="tech-title">
                Html
            </div>  
            <div class="tech-desc">
                <i class="fa-brands fa-html5" style="color: #737373;"></i>
            </div>
        </div>
        <div class="tech">
            <div class="tech-title">
                Github
            </div>  
            <div class="tech-desc">
                <i class="fa-brands fa-github" style="color: #737373;"></i>
            </div>
        </div>
    </div>
    <div class="seperator">

    </div>
</section>

<style>
    .techs{
        width: 100%;
        min-height: 100svh;
    }
    .techHeading{
        color: white;
        font-size: 35px;
        font-family: 'Microsoft Sans Serif', sans-serif;
        margin-bottom: 40px;
    }
    .tech-container{
        width: 100%;
        display: flex;
        justify-content: center;
        flex-wrap: wrap;
        column-gap: 20px;
        row-gap: 20px;
    }
    .tech{
        background-color:rgba(31, 31, 31, 1);
        cursor: pointer;
        padding: 15px;
        height: 170px;
        min-width: 170px;
        max-width: 230px;
        flex: 1;
        border-radius: 10px;
        font-family: 'Microsoft Sans Serif', sans-serif;
        box-shadow: 0 5px 5px rgb(7, 7, 7);
        display: grid;
        grid-template-rows: 15% 85%;
    }
    .tech-title{
        color: rgb(194, 194, 194);
        text-align: center;
        font-size: 1rem;
        font-weight: 500;
    }
    .tech-desc{
        display: flex;
        align-items: center;
        justify-content: center;
    }
    .tech-desc i{
        font-size: 8rem;
    }
    .tech:hover{
        background-color: rgb(20, 20, 20);
        opacity: .9;
    }
    .seperator{
        height: 1px;
        width: 100%;
        background-color: rgba(72, 72, 72, 1);
        margin: 40px 0 40px 0;
    }
    
</style>