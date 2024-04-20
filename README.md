
<!DOCTYPE html>
<html lang="en">


<head>

    <meta http-equiv="refresh" content="30">



   
    <meta name="viewpoint" content="width=device-width , initial-scale=1.0">
   
    <title>Nihal-Portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <link rel="stylesheet" href="sc1.css">
    <link rel="stylesheet" href="skills.css">
    <link rel="stylesheet" href="1st.css">
    <link rel="stylesheet" href="contactsection.css">

    <style>
         *{
            margin: 0;
            padding: 0;


        }

        body {
            background-color: rgb(0, 0, 31);
            color: white;
            font-family: "Poppins", sans-serif;

        }

        nav {
            position: sticky;
            top:0;
            cursor: pointer;
            background-image: url("bg2.jpg");
            background-size: cover;
            background-blend-mode: darken;
            display: flex;

            

            

            align-items: center;
            height: 100px;
            
            background-color: rgb(1, 1, 53) ;
            
            
            justify-content: space-around;



        }

        nav ul {
            display: flex;
            justify-content: space-evenly;

            align-items: center;

        }

        nav ul li {

            list-style: none;
            margin: 0 23px;

            display: flex;

        }

        nav ul li a {
            text-decoration: solid;
            color: white;



        }

        nav ul li a:hover {
            text-decoration: solid;
            color: rgb(85, 6, 158);
            font-size: 1.03rem;




        }

        .left {
            font-size: 1.5rem;
            color: aliceblue;
            
        }

        .section1 {
            background-image: url("bg2.jpg");
            background-size: cover;
            background-blend-mode: lighten;
            display: flex;
            justify-content: space-around;
            margin: 23px 0;
            

            align-items: center;

        }

        .section1>div {
            
            width: 40%;

        }

        .sec1leftdiv div {
            width: 60%;


        }

        .sec1leftdiv {

            font-size: 3rem;

        }

        .sec1leftdiv .buttons {
            padding: 50px 0;
        }

        .sec1leftdiv .btn1 {
            padding: 12px;
            background-color: rgb(12, 3, 20);
            color: white;
            border-radius: 6px;

            border: 2px solid white;

            font-size: 20px;
            cursor: pointer;

        }

        .sec1leftdiv .btn2 {
            padding: 12px;
            background-color: rgb(12, 3, 20);
            color: white;
            border-radius: 6px;

            border: 2px solid white;

            font-size: 20px;
            cursor: pointer;

        }


        .sec1rightdiv {
            margin: right -50px;
            ;

        }

        .sec1rightdiv img {
            margin: 58px 0;
            border-radius: 50%;
            transition: transform 0.3s ease-in-out;




        }

        .color {
            color: aqua;


        }

        #element {
            color: aqua;
        }

        main hr {
            border: 0;
            background-color: rgb(168, 101, 231);
            height: 0.5px;
            margin: 40px 84px;

        }

        .section2 {
            max-width: 80vw;
            margin: auto;
            height: 80vh;

        }

        .section2 h1 {

            font-size: 1.9rem;
            max-width: 80vw;
            margin: auto;

        }

        .section2 .box {
            background: white;
            width: 77vw;
            height: 2px;
            margin: 56px 0;
            display: flex;

        }

        .section2 .box .vertical {
            height: 98px;
            width: 1px;
            background-color: white;
            margin: 0 140px;

        }

        .vertical-title {
            font-size: 20px;
            position: relative;
            top: 75px;
            width: 150px;


        }

        .vertical-desc {
            position: relative;
            top: 90px;
            color: grey;


        }

        .img1 {
            width: 25px;
            position: relative;
            top: -32px;
            left: -9px;

        }

        .myskill {
            display: flex;
            align-items: center;
            margin: 14px 0px;
            font-size: 4rem;
        }



        @media screen and (max-width:1276px) {

            .box {
                flex-direction: column;
            }

            .section2 {
                height: 70vh;

            }

            .section2 .box .vertical {
                height: fit-content;


            }

            .box .vertical .img1 {
                top: 4px;

            }

            .box .vertical-title {
                margin-left: 40px;
                top: auto;
            }

            .box .vertical-desc {
                top: auto;
                margin-left: 40px;
            }


            .section1 {

                flex-direction: column-reverse;
            }

        }


       
    </style>

</head>
<script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>

<body>
    <header>
        <nav>
            <div class="left">Nihal's Portfolio</div>
            <div class="right">
                <ul>
                    <li><a href="index.html"> Home</a></li>
                    <li><a href="aboutme.html"> About</a></li>
                    <li><a href="myresume.html"> My Resume</a></li>
                    
                </ul>
            </div>


   



        </nav>
    </header>
    <main>
        <section class="section1">
            <div class="sec1leftdiv">
                Hey,I'm <span class="color">Nihal Anil Kumar</span>
                <div>a Web Developer and Student</div>
                <div>at VIT Vellore</div>

                <span id="element"></span>
                <script>
                    var typed = new Typed('#element', {
                        strings: ['Welcome', ':)'],
                        typeSpeed: 50,
                    });
                </script>
                <div class="buttons">
                    <a href="https://www.linkedin.com/in/nihal-anil-kumar-b96016275/">
                        <button class="btn1">
                            Visit Linkdin

                        </button></a>

                    <a href="https://github.com/NihalAnilKumar/psybaba">
                    <button class="btn2">Visit Github</button>
                    </a>
                </div>
                

            </div>
            <div class="sec1rightdiv">
                <img src="nih.jpg" alt="My Photo" style="transition: transform 0.3s ease-in-out;">
            </div>
        </section>
        <hr>

        <section class="section2">
            <h1>
                My Education
            </h1>
            <div class="box">
                <div class="vertical">
                    <img class="img1" src="Cambridge-School-Indirapuram.png" alt="">
                    <div class="vertical-title">
                        Delhi Public School Bangalore North
                    </div>
                    <div class="vertical-desc">
                        Primary Education
                        (2008-2010)
                    </div>
                </div>
                <div class="vertical"><img class="img1" src="channels4_profile.jpg" alt="">
                    <div class="vertical-title">
                        Delhi Public School Bangalore North
                    </div>
                    <div class="vertical-desc">
                        Secondary Education
                        Boards-91.6%(10th Class)
                    </div>
                </div>

                <div class="vertical"><img class="img1" src="512x512bb.jpg" alt="">
                    <div class="vertical-title">
                        Delhi Public School Bangalore North
                    </div>
                    <div class="vertical-desc">
                        Senior Secondary Education
                        Boards-88.9%
                    </div>
                </div>
                <div class="vertical"><img class="img1" src="124f55209dacad4cffd468e2997e1dec.jpg" alt="">
                    <div class="vertical-title">
                        VIT Vellore(2022-2026)
                    </div>
                    <div class="vertical-desc">
                        B.Tech Computer Science Core
                        CGPA-8.70
                    </div>
                </div>



            </div>
        </section>


        <hr>
        
            
            <section id="skills" class="skills-section">
                <h2><span class="myskill">My Skills</span></h2>
                <div class="skillsDiv" style="display: flex; flex-wrap: wrap; justify-content: space-around"> 
                    <div class="skill">
                    
                        <div class="skill-box frontend">
                            <h3>Frontend Development</h3>
                            <img src="IMG_4470.JPG" alt="Frontend Development" style="height: 200px;">
                            
                        </div>
                    </a>
                </div>
                <div class="skill">
                    
                        <div class="skill-box backend">
                            <h3>Backend Development</h3>
                            <img src="IMG_4471.JPG" alt="Backend Development" style="height: 200px;">
                            
                        </div>
                    </a>
                </div>
                <div class="skill">
                    
                        <div class="skill-box c_cpp">
                            <h3>C/C++</h3>
                            <img src="IMG_4472.JPG" alt="C/C++" style="height: 200px;" width="300px">
                            
                        </div>
                    </a>
                </div>
                <div class="skill">
                    
                        <div class="skill-box sql">
                            <h3>SQL</h3>
                            <img src="IMG_4473.PNG" alt="SQL" style="height: 200px; " width="300px">
                            
                        </div>
                    </a>
                </div>
                <div class="skill">
                    
                        <div class="skill-box sql">
                            <h3>Python</h3>
                            <img src="pyth.jpg" alt="SQL" style="height: 200px;" width="300px">
                            
                        </div>
                    </a>
                </div>
                <div class="skill">
                    
                        <div class="skill-box sql">
                            <h3>Java</h3>
                            <img src="javaa.jpg" alt="SQL" style="height: 200px;" width="300px ">
                            
                        </div>
                    </a>
                </div>
                <div class="skill">
                    
                        <div class="skill-box sql">
                            <h3>Excel</h3>
                            <img src="excs.jpg" alt="SQL" style="height: 200px;">
                            
                        </div>
                    </a>
                </div>

                </div>
                
            </section>

          
            <hr>

                    <section class="section contact-section">
                        <h2 class="section-heading" style="
                            text-align: center;
                             margin-bottom: 50px;
                             font-size: 2.5rem;
                            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
                               ">Contact Me</h2>
                        <form action="#" method="POST" class="contact-form">
                            <div class="form-group1">
                                <label for="name">Name:</label>
                                <input type="text" id="name" name="name" required>
                            </div>
                            <div class="form-group2">
                                <label for="email">Email:</label>
                                <input type="email" id="email" name="email" required>
                            </div>
                            <button type="submit">Submit</button>
                        </form>
                    </section>
        
        








    </main>
    <footer class="footer-distributed">

        <div class="footer-right">

            <a href="#"><img src="./github-icon.svg" width="35px"></img></a>
            <a href="#"><img src="./instagram-icon.svg" width="35px"></img></a>
            <a href="#"><img src="./facebook.svg" width="35px"></img></a>
            <a href="#"><img src="./twitter.svg" width="35px"></img></a>

        </div>

        <div class="footer-left">
            <p class="footerdescme">Nihal-Portfolio
            </p>

            

                <a class="link-1" href="nihalport.html">Home</a>

                <a href="www.Wix.com">Blog</a>

                <a href="aboutme.html">About</a>

                <a href>Faq</a>

                <a href="contact.html">Contact</a>
            

            <p>All Rights Reserved &copy; 2024</p>
        </div>



    </footer>
    <script src="2.js"></script>
</body>

</html>
