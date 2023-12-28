<script>
    
</script>

<div class="hero">
    <div class="hero-heading">
        <h1>
            Hey, I'm Reda 
            <span>
                Fullstack Developer
            </span>
        </h1>
    </div>
    <div class="hero-description">
        <div class="hero-button">
            <a href="/">
                <i class="fa-brands fa-linkedin"></i>
                Linkedin
            </a>
        </div>
        <div class="hero-button">
            <a href="/">
                <i class="fa-brands fa-github"></i>
                Github
            </a>
        </div>
        <div class="hero-button">
            <a href="/">
                <i class="fa-regular fa-envelope"></i>
                Email
            </a>
        </div>
    </div>
    <div class="hero-about">
        <p>
            Hi, I am Reda, Experienced full-stack developer from Morocco, With 3 years of expertise in React, Next, Nodejs, and MongoDB, Ready to create innovative web solutions!
        </p>
    </div>
    <div class="seperator"></div>
</div>

<style>
    .hero{
        max-width: 100%;
    }
    .hero-heading{
        padding: 10% 0 0 0;
    }
    .hero-heading h1{
        color: white;
        font-family: 'M PLUS 1p', sans-serif;
        font-size: 5rem;
        line-height: 145%;
        margin-bottom: 40px;
    }
    .hero-heading span{
        display: block;
        background-image: linear-gradient(90deg, rgba(190, 71, 201, 1),rgba(190, 71, 201, 1), rgba(218, 11, 147, 1));
        background-clip: text;
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        -moz-background-clip: text;
        -moz-text-fill-color: transparent;
    }
    .hero-description{
        display: flex;
    }
    .hero-button{
        background-color: rgba(45, 45, 45, 1);
        height: 60px;
        border-radius: 100px;
        display: flex;
        align-items: center;
        justify-content: center;
        margin: 0 20px 0 0;
        transition: .2s ease-in;
    }
    .hero-button a{
        color: rgba(218, 218, 218, 1);
        text-decoration: none;
        font-family: 'M PLUS 1p', sans-serif;
        font-weight: 500;
        font-size: 1.4rem;
        padding: 0 28px;
        height: 100%;
        width: 100%;
        display: flex;
        align-items: center;
        justify-content: center;
    }
    .hero-button:hover{
        background-color: white;
        scale: 1.1;
    }
    .hero-button:hover a{
        color: rgba(190, 71, 201, 1);
    }
    .hero-button a i{
        font-size: 30px;
        margin-right: 10px;
    }
    .hero-about{
        font-family: 'Microsoft Sans Serif', sans-serif;
        color: rgba(142, 142, 142, 1);
        width: 90%;
        line-height: 150%;
        font-size: 1.4rem;
        margin-top: 55px;
    }
    .seperator{
        height: 1px;
        width: 100%;
        background-color: rgba(72, 72, 72, 1);
        margin: 40px 0 40px 0;
    }


    @media screen and (max-width: 900px) {
        .hero-heading{
            padding: 5% 0 0 0;
        }
        .hero-heading h1{
            font-size: 2.7rem;
        }
        .hero-heading h1 span{
            font-size: 2.7rem;
        }
        .hero-button{
            height: 35px;
            margin: 0 10px 0 0;
        }
        .hero-button a{
            padding: 0 10px;
            font-size: 1rem;
        }
        .hero-button a i {
            font-size: 1rem;
        }
        .hero-about{
            font-size: 1rem;
            width: 95%;
            line-height: 160%;
        }
    }
</style>