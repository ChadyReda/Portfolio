<script>
   

</script>

<section class="timeline-section">
    <div class="timeline-heading">
        My TimeLine
    </div>
    <div class="timeline">
        <div class="container right">
            <div class="container-time">
                2021-09-27
            </div>
            <div class="container-desc">
                Learn the fundamentals of programming and coding with <span style="color: rgba(201, 205, 15, 1);">JavaScript</span>
            </div>
        </div>
        <div class="container left">
            <div class="container-time">
                2022-02-01
            </div>
            <div class="container-desc">
                Mastering Html Css for web developement
            </div>
        </div>
        <div class="container right">
            <div class="container-time">
                2022-07-05
            </div>
            <div class="container-desc">
                Create a full-stack apps using <span style="color: rgba(69, 119, 135, 1);">Express</span>
            </div>
        </div>
        <div class="container left">
            <div class="container-time">
                2023-01-20
            </div>
            <div class="container-desc">
                Learn Object oriented programming and Problem solving
            </div>
        </div>
        <div class="container right">
            <div class="container-time">
                2024-02-14
            </div>
            <div class="container-desc">
                Learn the fundamentals of React and sveltekit
            </div>
        </div>
    </div>
    <div class="seperator">

    </div>
</section>

<style>
    .timeline-section{
        width: 100%;
        min-height: 100svh;
    }
    .timeline-heading{
        font-family: 'Microsoft Sans Serif', sans-serif;
        font-size: 35px;
        margin-bottom: 40px;
        color: white;
        transform: translateX(-2px);
    }
    .timeline{
        position: relative;
        margin: 0 auto;
    }
    .timeline::after{
        content: '';
        position: absolute;
        width: 1px;
        background-color: rgba(72, 72, 72, 1);
        top: 0;
        bottom: 0;
        left: 50%;
        transform: translateX(0, -50%);
    }
    .container{
        min-height: 100px;
        position: relative;
        width: 50%;
        min-width: 300px;
        color: rgb(235, 235, 235);
        font-family: 'Microsoft Sans Serif', sans-serif;
        margin-bottom: 50px;
    }
    .left{
        text-align: right;
    }
    .right{
        right: -50%;
    }
    .right::after{
        content: "";
        position: absolute;
        top: 0;
        left: -7px;
        height: 15px;
        z-index: 1;
        width: 15px;
        border-radius: 50%;
        background-color: rgba(190, 71, 201, 1) ;
    }
    .left::after{
        content: "";
        position: absolute;
        top: 0;
        right: -8px;
        height: 15px;
        z-index: 1;
        width: 15px;
        border-radius: 50%;
        background-color: rgba(190, 71, 201, 1) ;
    }
    .left div{
        margin-right: 25px;
    }
    .right div{
        margin-left: 25px;
    }
    .container-time{
        color: rgb(99, 99, 99);
        margin-bottom: 25px;
    }
    .container-desc{
        font-size: 19px;
        line-height: 32px;
    }
    .seperator{
        height: 1px;
        width: 100%;
        background-color: rgba(72, 72, 72, 1);
        margin: 40px 0 40px 0;
    }
    @media screen and (max-width: 1000px){
        .timeline::after{
            left: 0;
        }
        .right{
            right: 0;
        }
        .left{
            text-align: left;
        }
        .left::after{
            left: -7px;
        }
        .left div{
            margin-left: 25px;
            margin-right: 0;
        }
    }

</style>