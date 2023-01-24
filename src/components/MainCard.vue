<template>
    <div class="main-container">
        <div class="container-one">
            <div class="profile">
                <img src="../assets/profilepic.jpeg" alt="">
                <h3>Name Here</h3>
                <p>Software Engineer</p>
            </div>
            <div class="social-links">
                <div class="link">
                        <a href="https://github.com/Fionan-Oxford">
                            <img src="../assets/github.png" alt="">
                            <h2>Github</h2>
                            </a>
                    </div>
                    <div class="link">
                        <a href="https://uk.linkedin.com/in/fion%C3%A1n-o-sullivan-15355778">
                            <img src="../assets/LinkedIn.png" alt="">
                            <h2>LinkedIn</h2>
                        </a>
                    </div>
            </div>
        </div>
        <div class="container-two">
        <div class="about-me">
            <h1></h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                Nostrum placeat accusamus quasi similique explicabo, 
                aspernatur obcaecati, consectetur, nisi dolore eos vero 
                omnis asperiores? Dolores saepe in consectetur ad? Quia,
                 eius.</p>
        </div>
        <div class="technology">
            <h1>Employment</h1>
            <div class="logos">
                <img src="../assets/jlr.png" alt="">
                <img src="../assets/streetdrone.png" alt="">

            </div>
        </div>
        <div class="button-container">
            <div class="projects-button">
                <a href="">My Projects</a>
            </div>
        </div>
    </div>
    </div>

</template>

<script>
export default {

}
</script>

<style scoped>
    img{
        height: 100px;
    }

    .main-container{
        display: flex;
        flex-direction: row;
        background-color: #cecece;
        border-radius: 25px;
    }

    .container-one{
        background-color: #ffb0b0;
        padding: 2.5%;
        width: 30%;
        border-radius: 25px;

    }

    .profile img{
        height: 15rem;
        border-radius: 50%;
    }

    .link a{
        text-decoration: none;
        color: #2c3e50;
        font-size: 10px;
    }

    .link img{
        height: 2rem;
    }
    .container-two{
        background-color: #cdcffc;
        margin: 2.5%;
        width: 70%;

    }

    .about-me{  
        text-align: left;
    }

    .logos  img{
        height: 2.5rem;
    }

    .button-container{
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-content: center;
    }
    
    .projects-button{
        background-color: #7c58ff;
        border-radius: 15px;
        padding: 5px;
        margin: 5px;
    }
    .projects-button a{
        text-decoration: none;
        color: #fff;

    }
</style>