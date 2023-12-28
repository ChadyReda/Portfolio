<script>
    import {
        HeroComponent as Hero,
        TimeLine,
        ProjectPage,
        Tech,
        Footer

    } from '$lib'

</script>

<section class="landing-page">
    <div class="page-container">
        <Hero></Hero>
        <TimeLine></TimeLine>
        <ProjectPage></ProjectPage>
        <Tech></Tech>
        <Footer></Footer>
    </div>
</section>

<style>
    @import '@fortawesome/fontawesome-free/css/all.css';
    @import url('https://fonts.googleapis.com/css2?family=M+PLUS+1p:wght@400;500;700&display=swap');
    @import url('https://fonts.cdnfonts.com/css/microsoft-sans-serif');
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@200;400;500&display=swap');
    .landing-page{
        background-color: black;
        background-image: url('/hoh.jpg');
        background-attachment: fixed;
        background-repeat: no-repeat;
        background-position: center;
        min-height: 100svh;
        width: 100%;
        display: flex;
        justify-content: center;
        z-index: 1;
    }
    .page-container{
        max-width: 60%;
        height: 100%;
    }


    @media screen and (max-width: 900px) {
        .page-container{
            max-width: 82%;
        }
    }
</style>