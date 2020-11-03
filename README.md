<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio</title>
    <link rel="stylesheet" type="text/css" href="css/style.css"/>
    <link rel="shortcut icon" type="" href="images/fav-icon.png">
    <!-- Font -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,300;0,500;0,600;0,800;1,400;1,700;1,900&display=swap" rel="stylesheet">


    <!--using FontAwesome--------------->
    <script src="https://kit.fontawesome.com/c8e4d183c2.js" crossorigin="anonymous"></script>
    
</head>
<body>
    <!-- main -->
    <div id="main">
        <!-- nav -->
        <nav>
            <!-- logo -->
            <a href="#" class="logo">
                <img src="images/fav-icon.png"/>
                <span>jul</span>
            </a>

            <!-- menu-btn--- -->
            <input class="menu-btn" type="checkbox" id="menu-btn">
            <label class="menu-icon" for="menu-btn">
                <span class="nav-icon"></span>
            </label>


            <!-- menu  -->
            <ul class="menu">
                <li><a href="#main">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#recent">Recent</a></li>
                <li><a href="#client">Client</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>

            <!-- say-hi -->
            <a href="#" class="hey">Say Hi</a>

        </nav>

        <!-- content -->
        <div class="content">
            
            <!-- model -->
            <div class=" col model">
                <img src="images/model.png" alt="" />
            </div>

            <!-- text -->
            <div class="col  main-text">
                <span>Hello, I'm</span>
                <h1>Ajul Kushwah</h1>
                <p>Hey, I am a full stack web developer.
                    Lorem ipsum dolor sit amet, consectetur
                    Lorem ipsum dolor sit amet, consectetur  
                </p>

                <!-- social link -->
                <a href="#" class="social-link">
                    <i class="fab fa-google-plus"></i>
                </a>
                <a href="#" class="social-link">
                    <i class="fab fa-linkedin"></i>
                </a>
                <a href="#" class="social-link">
                    <i class="fab fa-github"></i>
                </a>

                <!-- btn -->
                <a href="#" class="portfolio-btn">
                    See My portfolio
                </a>
            </div>
        </div>

    </div>
    

    <div id="about">
        
        <!-- about-text -->
        <div class="about-text">
            
            <h3>About</h3>
            
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. 
            Fugit quas harum quis nemo temporibus blanditiis minima repudiandae error! Eum, ea. 
            Cupiditate odit illo est iusto enim. Fuga, velit soluta. Voluptates?
            </p>
        
        </div>
        
        <!-- img -->
        <div class=" about-img">
            <img src="images/model.png">
        </div>

    </div>

    <!-- skills -->
    <div id="skills">
        
        <!-- text -->
        <div class="skill-text">
            <!-- heading -->

            <div class="skill-heading">
                <span>My Skills</span>
                <h2>My Experties</h2>
            </div>

            <!-- skill-box-container -->
            <div class="s-box-container">

                <!-- skill-box 1 -->
                <div class="skill-box">
                    
                    <!-- icon -->
                    <div class="s-box-icon">
                        <i class="fab fa-html5"></i>
                    </div>

                    <!-- skill-box-text -->
                    <div class="s-box-text">
                        <strong>Python</strong>
                        <p>I have 3 years experience in HTML and i completed 100+ HTML project.</p>
                    </div>
                </div>

                <!-- skill-box 2 -->
                <div class="skill-box">
                    
                    <!-- icon -->
                    <div class="s-box-icon">
                        <i class="fab fa-html5"></i>
                    </div>

                    <!-- skill-box-text -->
                    <div class="s-box-text">
                        <strong>Django</strong>
                        <p>I have 3 years experience in HTML and i completed 100+ HTML project.</p>
                    </div>
                </div>

                <!-- skill-box 3 -->
                <div class="skill-box">
                    
                    <!-- icon -->
                    <div class="s-box-icon">
                        <i class="fab fa-html5"></i>
                    </div>

                    <!-- skill-box-text -->
                    <div class="s-box-text">
                        <strong>C++</strong>
                        <p>I have 3 years experience in HTML and i completed 100+ HTML project.</p>
                    </div>
                </div>

            </div>    
        </div>

        <!-- skills set -->
        <div class="skills-set">
            <h4>Programming Languages</h4>
            <button class="skill-btn">C</button>
            <button class="skill-btn">C++</button>
            <button class="skill-btn">Java</button>
            <button class="skill-btn">Python</button>
            
            <h4>Web Development</h4>
            <button class="skill-btn">HTML5</button>
            <button class="skill-btn">CSS3</button>
            <button class="skill-btn">JavaScript</button>
            <button class="skill-btn">Bootstrap</button>
            <button class="skill-btn">JQuery</button>
            <button class="skill-btn">Ajax</button>

            
            <h4>Database Technology</h4>
            <button class="skill-btn">SQL</button>
            <button class="skill-btn">PL/SQL</button>
            <button class="skill-btn">MySQL</button>
            <button class="skill-btn">MangoDB</button>
        </div>
        <!--img--------------->
        <!-- <div class="skill-img">
            <img src="images/skill2.png"/>	
        </div> -->

    </div>
    
    <!--  ----------------projects--------------- -->

    <section id="projects">

        <!-- heading -->
        <div class="client-heading">
            <span>My Acadmic</span>
            <h3>Projects</h3>
        </div>

        <!-- client-box-container------ -->
        <div class="c-box-container">
            
            <!-- Box -1 -->
            <div class="project-box">
                
                <!-- img----->
                <img src="images/book-solid.svg" alt="">

                <!-- project title -->
                <h3>Smart Book Store</h3>
        
                <!--details/comment------>
                <p>Desktop Application Book Store Management System.  random sentence isn't quite enough, the next logical step is to find a random paragraph. </p>
                <!--btn--------->
                <a href="#">Read More</a>

            </div>

            <!-- Box -2 -->
            <div class="project-box">
                
                <!-- img----->
                <img src="images/client-2.png" alt="">
            
                <!-- project title -->
                <h3>Tribal Talent Repository</h3>
        
                <!--details/comment------>
                <p>If you're looking for random paragraphs, you've come to the right place. When a random word or a random sentence isn't quite enough, the next logical step is to find a random paragraph. </p>
                <!--btn--------->
                <a href="#">Read More</a>
                
            </div>

            <!-- Box -3 -->
            <div class="project-box">
                
                <!-- img----->
                <img src="images/client-3.png" alt="">
                
                <!-- project title -->
                <h3>Social Media</h3>
        
                <!--details/comment------>
                <p>If you're looking for random paragraphs, you've come to the right place. When a random word or a random sentence isn't quite enough, the next logical step is to find a random paragraph. </p>
                <!--btn--------->
                <a href="#">Read More</a>
                
            </div>

            
        </div>
    </section>

    <section id="projects">

        <!-- heading -->
        <div class="client-heading">
            <span>My Personal</span>
            <h3>Projects</h3>
        </div>

        <!-- client-box-container------ -->
        <div class="c-box-container">
            
            <!-- Box -1 -->
            <div class="project-box">
                
                <!-- img----->
                <img src="images/book-solid.svg" alt="">

                <!-- project title -->
                <h3>Digi Course</h3>
        
                <!--details/comment------>
                <p>If you're looking for random paragraphs, you've come to the right place. When a random word or a random sentence isn't quite enough, the next logical step is to find a random paragraph. </p>
                <!--btn--------->
                <a href="#">Read More</a>

            </div>

            
            <!-- Box -2 -->
            <div class="project-box">
                
                <!-- img----->
                <img src="images/client-2.png" alt="">
            
                <!-- project title -->
                <h3>Covid19 Live</h3>
        
                <!--details/comment------>
                <p>If you're looking for random paragraphs, you've come to the right place. When a random word or a random sentence isn't quite enough, the next logical step is to find a random paragraph. </p>
                <!--btn--------->
                <a href="#">Read More</a>
                
            </div>

            <!-- Box -3 -->
            <div class="project-box">
                
                <!-- img----->
                <img src="images/client-3.png" alt="">
                
                <!-- project title -->
                <h3>Ecommerse</h3>
        
                <!--details/comment------>
                <p>If you're looking for random paragraphs, you've come to the right place. When a random word or a random sentence isn't quite enough, the next logical step is to find a random paragraph. </p>
                <!--btn--------->
                <a href="#">Read More</a>
                
            </div>

            <!-- Box -1 -->
            <div class="project-box">
                
                <!-- img----->
                <img src="images/client-1.png" alt="">
        
                <!-- project title -->
                <h3>Smart Book Store</h3>
        
                <!--details/comment------>
                <p>If you're looking for random paragraphs, you've come to the right place. When a random word or a random sentence isn't quite enough, the next logical step is to find a random paragraph. </p>
                <!--btn--------->
                <a href="#">Read More</a>

            </div>

            <!-- Box -2 -->
            <div class="project-box">
                
                <!-- img----->
                <img src="images/client-2.png" alt="">
            
                <!-- project title -->
                <h3>Smart Book Store</h3>
        
                <!--details/comment------>
                <p>If you're looking for random paragraphs, you've come to the right place. When a random word or a random sentence isn't quite enough, the next logical step is to find a random paragraph. </p>
                <!--btn--------->
                <a href="#">Read More</a>
                
            </div>

            <!-- Box -3 -->
            <div class="project-box">
                
                <!-- img----->
                <img src="images/client-3.png" alt="">
                
                <!-- project title -->
                <h3>Smart Book Store</h3>
         
                <!--details/comment------>
                <p>If you're looking for random paragraphs, you've come to the right place. When a random word or a random sentence isn't quite enough, the next logical step is to find a random paragraph. </p>
                <!--btn--------->
                <a href="#">Read More</a>
                
            </div>
        </div>
    </section>





    <!-- recent project -->
    <section id="recent">
        <!-- heading -->
        <div class="recent-heading">
            <span>Recent</span>
            <h3>Recent Doing Project Design</h3>
        </div>

        <!-- img -->
        <div class="recent-img">
            <img src="images/recent.png">
        </div>

        <!-- recent btn -->
        <a href="#" class="recent-btn">View Design</a>

    </section>


    <!--  client-------------- -->
    <section id="client">

        <!-- heading -->
        <div class="client-heading">
            <span>Comment</span>
            <h3>Client's Say</h3>
        </div>

        <!-- client-box-container------ -->
        <div class="c-box-container">
            
            <!-- Box -1 -->
            <div class="client-box">
                
                <!-- img----->
                <img src="images/client-1.png" alt="">
                
                <!-- star/reviews---------->
                <div class="star">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                </div>

                <!--details/comment------>
                <p>If you're looking for random paragraphs, you've come to the right place. When a random word or a random sentence isn't quite enough, the next logical step is to find a random paragraph. </p>
                <!--btn--------->
                <a href="#">Read More</a>

            </div>

            <!-- Box -2 -->
            <div class="client-box">
                
                <!-- img----->
                <img src="images/client-2.png" alt="">
                
                <!-- star/reviews---------->
                <div class="star">
                    <i class="fab fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                </div>

                <!--details/comment------>
                <p>If you're looking for random paragraphs, you've come to the right place. When a random word or a random sentence isn't quite enough, the next logical step is to find a random paragraph. </p>
                <!--btn--------->
                <a href="#">Read More</a>
                
            </div>

            <!-- Box -3 -->
            <div class="client-box">
                
                <!-- img----->
                <img src="images/client-3.png" alt="">
                
                <!-- star/reviews---------->
                <div class="star">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                </div>

                <!--details/comment------>
                <p>If you're looking for random paragraphs, you've come to the right place. When a random word or a random sentence isn't quite enough, the next logical step is to find a random paragraph. </p>
                <!--btn--------->
                <a href="#">Read More</a>
                
            </div>
        </div>
    </section>


    <!--contact------------------------->
	<section id="contact">
        <!--img-------->
        <img src="images/contact.svg"/>
        
        <!--heading---------------->
        <h3>Get The Best Project Estimation</h3>

        <!-- contact details -->
        <a href="mailto:ajulkushwah786@gmail.com"> 
            <div class="email">
                <i class="fas fa-envelope-square"></i>
                <h3>Ajulkushwah786@gmail.com</h3>
            </div>
        </a>

        <a href="tel:8085555743">
            <div class="phone">
                <i class="fas fa-phone"></i>
                <h3>+91 8085555743</h3>
            </div>
        </a>

        <a href="#">
            <div class="phone">
                <i class="fas fa-location-arrow"></i>
                <h3>Toppura Vidisha,MP ,India</h3>
            </div>
        </a>

        <!--input----------------->
        <div class="contact-input">
            <input type="email" placeholder="Example@gmail.com"/>
            <a href="#">Continue</a>
        </div>
        
    </section>
    
    <!--footer--------->
    
    <footer>
        <!-- <img src="images/fav-icon.png" 
        width="30px" height="30px" 
        style="margin-top: 5px;" class="logo-img"> -->
        <!-- <span>jul</span> -->
        <p>My Portfolio,  Website</p>
        <p>Copyright 2020 - Ajul Kushwah</p>
    </footer>
    
</body>
</html>
