<template>
<div class="wrapper">
    <div class = "main-container">
        <div class = "container-one">
            <div class = "profile">
                <img src="../assets/profilepic.png" alt = "">
                <h3> Fahadur Rahman </h3>
                <p> Front End Developer </p>
            </div>
            <div class = "socialmedia">
                <div class="links">
                    <a href="https://github.com/Fahadoid">
                        <img src="../assets/GitHub.png" alt="">
                        <h2>Github</h2>
                    </a>
                </div>
                <div class="links">
                    <a href="https://www.linkedin.com/in/fahadur-rahman-415325274/">
                        <img src="../assets/linkedin.png" alt="">
                        <h2>LinkedIn</h2>
                    </a>
                </div>
            </div>
        </div>
        <div class="container-two">
            <div class="about-me">
                <h1>About Me</h1>
                <p>Hello there, I'm Fahadur Rahman, a Computer Science graduate from Queen Mary University. My passion for technology and problem-solving has led me on an exciting journey through software development and beyond. </p>
                <p>I've always been fascinated by the limitless possibilities of coding. Whether I'm developing an intricate algorithm, crafting an elegant user interface, or troubleshooting a challenging bug, I find immense satisfaction in the creative process of turning ideas into functional software. </p>
                <p>In addition to my love for coding, I'm an avid gamer and chess enthusiast. There's something incredibly rewarding about the strategic depth of both gaming and chess, and they provide the perfect balance to my technical pursuits. </p>
                <p>Throughout my University journey, I've had the opportunity to work on diverse projects, including creating an auction website, an employee portal, a weather application, and a Bayesian inference algorithm using discretization. These experiences have honed my technical skills and allowed me to explore different facets of software development.</p>
                <p>I believe in the power of technology to transform ideas into reality, and I'm always eager to embrace new challenges and opportunities in the ever-evolving world of computer science.</p>
                
            </div>
            <div class="technologies">
                <h1>Technologies Studied</h1>
                <div class="logos">
                <img src = "../assets/javascript.png" alt = "">
                <img src = "../assets/java.png" alt = "">
                <img src = "../assets/python.png" alt = "">
                <img src = "../assets/css.png" alt = "">
                <img src = "../assets/html.png" alt = "">
                
                </div>
            </div>
            <div class="button-container">
                <div class="project-buttons">
                    <a href="../assets/Fahadur_Rahman_CV.docx" download>My Resume</a>
                </div>
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

    .wrapper {
        display: flex;
        justify-content: center;
    }

    img {
        height: 30px;
        
    }    

    .main-container {
        display: flex;
        flex-direction: row;
        background-color: #cecece;
        border-radius: 25px;
        width: 60%;
        background-color: #a0d4ff;
        
    }

    .container-one{
        background-color: #1a8eed;
        width: 20%;
        padding: 2.5%;
        border-radius: 25px;
        box-shadow: rgba(0,0,0,0,24) 0px 3px 8px;
    }

    .profile img {
        height: 7rem;
        border-radius: 50%;
    }

    .links a{
        text-decoration: none;
        color: #2c3e50;
        font-size: 10px;
    }

    .links img {
        height: 2rem;

    }

    .container-two {
        background-color: a0d4ff;
        margin: 2.5%;
        width:80%;
    }

    .about-me {
        text-align: left;
    }

    .logos img{
        height: 2.5rem;
    }
    
    .button-container{
        margin-top: 5%;
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
    }
    .project-buttons {
        background-color: #005ca4;
        border-radius: 15px;
        padding: 5px;
        margin: 5px;

    }
    .project-buttons a{
        text-decoration: none;
        color: #fff;
    }

    @media only screen and (max-width : 950px) {
        .main-container {
            width: 95%
        }
    }
</style>