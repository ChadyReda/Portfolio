<script>

</script>

<section class="footer">
    <div class="sentence">
        <h1>Thanks for scolling</h1>
    </div>
    <div class="resumé-container">
        <a href="#">
            Resume
            <i class="fa-solid fa-download"></i>
        </a>
    </div>
    <div class="seperator">

    </div>
    <div class="end">
        All right reserved - by Reda - 2024
        <p>This site was made using <span style="color: orangered;">sveltekit</span></p>
    </div>
</section>

<style>
    .footer{
        width: 100%;
        font-family: 'Microsoft Sans Serif', sans-serif;
    }
    .sentence{
        font-size: 1.5rem;
        background-image: linear-gradient(90deg, rgba(190, 71, 201, 1),rgba(190, 71, 201, 1), rgba(218, 11, 147, 1));
        background-clip: text;
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        -moz-background-clip: text;
        -moz-text-fill-color: transparent;
    }
    .sentence h1{
        margin: 0;
    }
    .seperator{
        height: 1px;
        width: 100%;
        background-color: rgba(72, 72, 72, 1);
        margin: 40px 0 40px 0;
    }
    .resumé-container{
        height: 80px;
        display: flex;
        align-items: center;
    }
    .resumé-container a{
        color: rgba(200, 200, 200, 1);
        background-color: rgba(31, 31, 31, 1) ;
        padding: 18px 30px;
        border-radius: 100px;
        font-size: 20px;
        text-decoration: none;
        margin-top: 25px;
    }
    .resumé-container a i{
        margin-left: 5px;
    }
    .end{
        padding-bottom: 40px;
        color: rgba(72, 72, 72, 1);
    }
</style>