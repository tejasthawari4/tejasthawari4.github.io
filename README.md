<!DOCTYPE html>
<html lang="en">

<head>

  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>TEJAS THAWARI</title>

  <!-- AOS -->
  <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />

  <!-- FAVICON -->
  <link class="favicon" rel="icon" type="image/img" sizes="32x32" href="images/favicon-32x32.png">

  <!-- Google material icons -->
  <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet" />

   <!-- CSS -->
  <link rel="stylesheet" href="style.css" />

   <!-- FONT AWESOME -->
  <script src="https://kit.fontawesome.com/3d143c9fe7.js" crossorigin="anonymous"></script>

   <!-- TYPE JS -->
  <script src="https://cdnjs.cloudflare.com/ajax/libs/typed.js/2.0.12/typed.min.js"
    integrity="sha512-3J8teBiHrSyaaRBajZyIEtpDsXdPq1gsznKWIVb5CnorQuFhjWGhWe54z8YNnHHr7MZuExb9m5kvf964HiT1Sw=="
    crossorigin="anonymous" referrerpolicy="no-referrer"></script>

   <!-- jQUERY -->
  <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>

   <!-- SWEET ALERT -->
  <script src="https://cdn.jsdelivr.net/npm/sweetalert2@11"></script>

   <!-- EMAIL JS -->
  <script type="text/javascript" src="https://cdn.jsdelivr.net/npm/emailjs-com@3/dist/email.min.js"></script>
  <script type="text/javascript">
    (function () {
      emailjs.init("{{YOUR USER KEY}}");
    })();
  </script>

</head>

<body>
    <nav class="navbar">
      <div class="progress-container">
        <div class="progress-bar" id="myBar"></div>
      </div> 
      <div class="max-width">
        <div class="logo">
          <a href="#"><span>www.</span>tejas-thawari<span>.tk</span></a>
        </div>
        <ul class="menu">
          <li><a href="#home" class="menu-btn">Home</a></li>
          <li><a href="#about" class="menu-btn">About</a></li>
          <li><a href="#services" class="menu-btn">Projects</a></li>
          <li><a href="#skills" class="menu-btn">Skills</a></li>
          <li><a href="#contact" class="menu-btn">Contact</a></li>
        </ul>
        <div class="menu-btn">
          <i class="material-icons">menu</i>
        </div>
      </div>
    </nav>
  <!-- Scroll to top button -->
    <button id="btnScrollToTop">
      <i class="material-icons">arrow_upward</i>
    </button>
    
  <!-- home section start-->
  <section class="home" id="home">
    <div class="max-width">
      <div class="home-content">
        <div class="text-1" data-aos="fade-up">Hello, my name is</div>
        <div class="text-2">TEJAS THAWARI</div>
        <div class="text-3">Im a <span class="typing"></span></div>
      </div>
    </div>
  </section>

  <!-- about section -->
  <section class="about" id="about">
    <div class="max-width">
      <h2 class="title" data-aos="fade-down" >About Me</h2>
      <div class="about-content">
        <div class="column left" data-aos="fade-right" >
          <img src="gif\thoughtworks-gif_dribbble.gif" alt="" style="border-radius: 50%;"/>
        </div>
        <div class="column right" data-aos="fade-up">
          <div class="text">
            I'm TEJAS THAWARI and Im a <span class="typing-2"></span>
          </div>
          <p class="paragraph">
            I have passion for building clean web applications with intuitive functionality. I enjoy the process of turning ideas into reality using creative solutions. I’m always curious about learning new skills, tools, and concepts. In addition to working on various solo full stack projects, I have worked with creative teams, which involves daily stand-ups and communications, source control, and project management.</p>
          <a href="https://drive.google.com/drive/u/2/folders/1qfv1LxxDHgez0SpD8bUtK8qh_p4kqaPI">Download
            Resume</a>
        </div>
      </div>
    </div>
  </section>

  <!-- Services Section -->
  <section class="services" id="services">
    <div class="max-width">
      <h2 class="title" data-aos="fade-down">My Projects</h2>
      <div class="serv-content">
        <div class="card" data-aos="flip-left">
          <div class="box">
            <i class="fas fa-laptop-code"></i>
            <div class="text"><a href="https://github.com/tejasthawari4/Alert-System-with-Face-Mask-Detection" style="color: white;">PROJECT 1</a></div>
            <p><a href="https://github.com/tejasthawari4/Alert-System-with-Face-Mask-Detection" style="color: white;">
              An automated face mask detection system tells whether a person is wearing a face mask or not. It is useful to avoid the spread of diseases which spreads through the air.</p>
            </a>
            </div>
        </div>

        <div class="card" data-aos="flip-left">
          <div class="box">
            <i class="fas fa-code"></i>
            <div class="text"><a href="https://github.com/tejasthawari4/Stayfit" style="color: white;">PROJECT 2</a></div>
            <p><a href="https://github.com/tejasthawari4/Alert-System-with-Face-Mask-Detection" style="color: white;">
              Fitness application that’s used to keep track of your physical fitness data, daily calorie count, invite friends to work out together and ultimately get healthy.</p>
            </a></div>
        </div>

        <div class="card" data-aos="flip-left">
          <div class="box">
            <i class="fas fa-mobile-alt"></i>
            <div class="text"><a href="https://github.com/tejasthawari4/iCinema" style="color: white;">PROJECT 3</a></div>
            <p><a href="https://github.com/tejasthawari4/Alert-System-with-Face-Mask-Detection" style="color: white;">
              A full-stack MERN website for movie theaters that allows users to browse for films and filter them by available categories and ratings, as well as enables administrators to add new films to the list.</p>
            </a></div>
        </div>
      </div>
    </div>
  </section>

  <!-- skills section services -->
  <section class="skills" id="skills">
    <div class="max-width" data-aos="fade-down">
      <h2 class="title" data-aos="fade-up">My Skills</h2>
      <div class="skills-content">
        <div class="column left">
          <div class="text">
            My creative skills & experiences.
          </div>
          <p class="paragraph-2">
            Expertise in web development with React.js, Express.js, Node.js, and databases like MongoDB and SQL.
            Proficiency in multiple programming languages, including Java, C++, Python, and experience in implementing machine learning algorithms.</p>
          <a href="#about">Read More</a>
        </div>
        <div class="column right skill-box">
          <div class="icons">
            <img src="images\skill-icons\icons8-css3.svg" alt="css" id="css-icon" data-aos="flip-left">
            <img src="images\skill-icons\icons8-javascript.svg" alt="js" id="js-icon" data-aos="flip-left">
            <img src="images\skill-icons\icons8-react-native.svg" alt="react" id="react-icon" data-aos="flip-left">
            <img src="images\skill-icons\icons8-flutter.svg" alt="flutter" id="flutter-icon" data-aos="flip-left">
          </div>
          <div class="icons">
            <img src="images\skill-icons\icons8-html-5.svg" alt="html", id="html-icon" data-aos="flip-left">
            <img src="images\skill-icons\icons8-nodejs.svg" alt="nodedjs" id="nodejs-icon" data-aos="flip-left">
            <img src="images\skill-icons\icons8-visual-studio-code-2019.svg" alt="vscode" id="vscode-icon" data-aos="flip-left">
            <img src="images\skill-icons\icons8-c++.svg" alt="c++" id="cpp-icon" data-aos="flip-left">
      </div>
  </section>

  <!-- Contact Section -->
  <section class="contact" id="contact">
    <div class="max-width">
      <h2 class="title" data-aos="fade-down">Contact Me</h2>
      <div class="contact-content">
        <div class="column left" data-aos="flip-left">
          <div class="text">Let's Get in Touch</div>
          <p class="paragraph-3">Interested in working together? We should queue up a chat. I’ll buy the coffee!!</p>
          <div class="icons">
            <div class="row">
              <i class="fas fa-user"></i>
              <div class="info">
                <div class="head">Name</div>
                <div class="sub-title">TEJAS THAWARI</div>
              </div>
            </div>
            <div class="row">
              <i class="fas fa-map-marker-alt"></i>
              <div class="info">
                <div class="head">Address</div>
                <div class="sub-title">Alandi,Pune 412105.</div>
              </div>
            </div>
            <div class="row">
              <i class="fas fa-envelope"></i>
              <div class="info">
                <div class="head">Email</div>
                <div class="sub-title">Tejas.thawari2015@gmail.com</div>
              </div>
            </div>
          </div>
        </div>
        <div class="column right" data-aos="flip-right">
          <div class="text">
            Message Me
          </div>
          <form action="#Contact">
            <div class="fields">
              <div class="field name">
                <input type="text" id="fromName" placeholder="Name" required autocomplete="off">
              </div>
              <div class="field email">
                <input type="email" id="emailSender" placeholder="Email" required autocomplete="off">
              </div>
            </div>
            <div class="field">
              <input type="text" id="subjectSender" placeholder="Subject" required autocomplete="off">
            </div>
            <div class="field textarea">
              <textarea cols="30" rows="10" id="message" placeholder="Message" required autocomplete="off"></textarea>
            </div>
            <div class="button">
              <button onclick='sendMail()' type="submit">Send Message</button>
            </div>
          </form>
        </div>
      </div>
    </div>
  </section>
  <!-- footer section start -->
  <footer>
    <div class="text-center">
      <span>
        Created By <a href="#">TEJAS THAWARI</a> | <span class="far fa-copyright"> </span> <script>document.write(new Date().getFullYear())</script> All rights reserved.
        <div>
          <a href="https://in.linkedin.com/in/tejas-thawari"><i class="fab fa-linkedin"></i></a>
          <a href="https://github.com/tejasthawari4"><i class="fab fa-github"></i></a>
          <a href="https://www.tsthawari.blogspot.com/"><i class="fab fa-blogger"></i></a>
        </div>
      </span>
    </div>
  </footer>
  <script src="script.js"></script>
  <script>
    // When the user scrolls the page, execute myFunction 
    window.onscroll = function() {myFunction()};
    
    function myFunction() {
      var winScroll = document.body.scrollTop || document.documentElement.scrollTop;
      var height = document.documentElement.scrollHeight - document.documentElement.clientHeight;
      var scrolled = (winScroll / height) * 100;
      document.getElementById("myBar").style.width = scrolled + "%";
    }
    </script>
    <script src="https://unpkg.com/aos@next/dist/aos.js"></script>
    <script>AOS.init({easing : 'ease-in',delay: 100,duration: 300,offset:100});window.addEventListener('load', AOS.refresh);</script>
</body>

</html><!DOCTYPE html>
<html lang="en">

<head>

  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>TEJAS THAWARI</title>

  <!-- AOS -->
  <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />

  <!-- FAVICON -->
  <link class="favicon" rel="icon" type="image/img" sizes="32x32" href="images/favicon-32x32.png">

  <!-- Google material icons -->
  <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet" />

   <!-- CSS -->
  <link rel="stylesheet" href="style.css" />

   <!-- FONT AWESOME -->
  <script src="https://kit.fontawesome.com/3d143c9fe7.js" crossorigin="anonymous"></script>

   <!-- TYPE JS -->
  <script src="https://cdnjs.cloudflare.com/ajax/libs/typed.js/2.0.12/typed.min.js"
    integrity="sha512-3J8teBiHrSyaaRBajZyIEtpDsXdPq1gsznKWIVb5CnorQuFhjWGhWe54z8YNnHHr7MZuExb9m5kvf964HiT1Sw=="
    crossorigin="anonymous" referrerpolicy="no-referrer"></script>

   <!-- jQUERY -->
  <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>

   <!-- SWEET ALERT -->
  <script src="https://cdn.jsdelivr.net/npm/sweetalert2@11"></script>

   <!-- EMAIL JS -->
  <script type="text/javascript" src="https://cdn.jsdelivr.net/npm/emailjs-com@3/dist/email.min.js"></script>
  <script type="text/javascript">
    (function () {
      emailjs.init("{{YOUR USER KEY}}");
    })();
  </script>

</head>

<body>
    <nav class="navbar">
      <div class="progress-container">
        <div class="progress-bar" id="myBar"></div>
      </div> 
      <div class="max-width">
        <div class="logo">
          <a href="#"><span>www.</span>tejas-thawari<span>.tk</span></a>
        </div>
        <ul class="menu">
          <li><a href="#home" class="menu-btn">Home</a></li>
          <li><a href="#about" class="menu-btn">About</a></li>
          <li><a href="#services" class="menu-btn">Projects</a></li>
          <li><a href="#skills" class="menu-btn">Skills</a></li>
          <li><a href="#contact" class="menu-btn">Contact</a></li>
        </ul>
        <div class="menu-btn">
          <i class="material-icons">menu</i>
        </div>
      </div>
    </nav>
  <!-- Scroll to top button -->
    <button id="btnScrollToTop">
      <i class="material-icons">arrow_upward</i>
    </button>
    
  <!-- home section start-->
  <section class="home" id="home">
    <div class="max-width">
      <div class="home-content">
        <div class="text-1" data-aos="fade-up">Hello, my name is</div>
        <div class="text-2">TEJAS THAWARI</div>
        <div class="text-3">Im a <span class="typing"></span></div>
      </div>
    </div>
  </section>

  <!-- about section -->
  <section class="about" id="about">
    <div class="max-width">
      <h2 class="title" data-aos="fade-down" >About Me</h2>
      <div class="about-content">
        <div class="column left" data-aos="fade-right" >
          <img src="gif\thoughtworks-gif_dribbble.gif" alt="" style="border-radius: 50%;"/>
        </div>
        <div class="column right" data-aos="fade-up">
          <div class="text">
            I'm TEJAS THAWARI and Im a <span class="typing-2"></span>
          </div>
          <p class="paragraph">
            I have passion for building clean web applications with intuitive functionality. I enjoy the process of turning ideas into reality using creative solutions. I’m always curious about learning new skills, tools, and concepts. In addition to working on various solo full stack projects, I have worked with creative teams, which involves daily stand-ups and communications, source control, and project management.</p>
          <a href="https://drive.google.com/drive/u/2/folders/1qfv1LxxDHgez0SpD8bUtK8qh_p4kqaPI">Download
            Resume</a>
        </div>
      </div>
    </div>
  </section>

  <!-- Services Section -->
  <section class="services" id="services">
    <div class="max-width">
      <h2 class="title" data-aos="fade-down">My Projects</h2>
      <div class="serv-content">
        <div class="card" data-aos="flip-left">
          <div class="box">
            <i class="fas fa-laptop-code"></i>
            <div class="text"><a href="https://github.com/tejasthawari4/Alert-System-with-Face-Mask-Detection" style="color: white;">PROJECT 1</a></div>
            <p><a href="https://github.com/tejasthawari4/Alert-System-with-Face-Mask-Detection" style="color: white;">
              An automated face mask detection system tells whether a person is wearing a face mask or not. It is useful to avoid the spread of diseases which spreads through the air.</p>
            </a>
            </div>
        </div>

        <div class="card" data-aos="flip-left">
          <div class="box">
            <i class="fas fa-code"></i>
            <div class="text"><a href="https://github.com/tejasthawari4/Stayfit" style="color: white;">PROJECT 2</a></div>
            <p><a href="https://github.com/tejasthawari4/Alert-System-with-Face-Mask-Detection" style="color: white;">
              Fitness application that’s used to keep track of your physical fitness data, daily calorie count, invite friends to work out together and ultimately get healthy.</p>
            </a></div>
        </div>

        <div class="card" data-aos="flip-left">
          <div class="box">
            <i class="fas fa-mobile-alt"></i>
            <div class="text"><a href="https://github.com/tejasthawari4/iCinema" style="color: white;">PROJECT 3</a></div>
            <p><a href="https://github.com/tejasthawari4/Alert-System-with-Face-Mask-Detection" style="color: white;">
              A full-stack MERN website for movie theaters that allows users to browse for films and filter them by available categories and ratings, as well as enables administrators to add new films to the list.</p>
            </a></div>
        </div>
      </div>
    </div>
  </section>

  <!-- skills section services -->
  <section class="skills" id="skills">
    <div class="max-width" data-aos="fade-down">
      <h2 class="title" data-aos="fade-up">My Skills</h2>
      <div class="skills-content">
        <div class="column left">
          <div class="text">
            My creative skills & experiences.
          </div>
          <p class="paragraph-2">
            Expertise in web development with React.js, Express.js, Node.js, and databases like MongoDB and SQL.
            Proficiency in multiple programming languages, including Java, C++, Python, and experience in implementing machine learning algorithms.</p>
          <a href="#about">Read More</a>
        </div>
        <div class="column right skill-box">
          <div class="icons">
            <img src="images\skill-icons\icons8-css3.svg" alt="css" id="css-icon" data-aos="flip-left">
            <img src="images\skill-icons\icons8-javascript.svg" alt="js" id="js-icon" data-aos="flip-left">
            <img src="images\skill-icons\icons8-react-native.svg" alt="react" id="react-icon" data-aos="flip-left">
            <img src="images\skill-icons\icons8-flutter.svg" alt="flutter" id="flutter-icon" data-aos="flip-left">
          </div>
          <div class="icons">
            <img src="images\skill-icons\icons8-html-5.svg" alt="html", id="html-icon" data-aos="flip-left">
            <img src="images\skill-icons\icons8-nodejs.svg" alt="nodedjs" id="nodejs-icon" data-aos="flip-left">
            <img src="images\skill-icons\icons8-visual-studio-code-2019.svg" alt="vscode" id="vscode-icon" data-aos="flip-left">
            <img src="images\skill-icons\icons8-c++.svg" alt="c++" id="cpp-icon" data-aos="flip-left">
      </div>
  </section>

  <!-- Contact Section -->
  <section class="contact" id="contact">
    <div class="max-width">
      <h2 class="title" data-aos="fade-down">Contact Me</h2>
      <div class="contact-content">
        <div class="column left" data-aos="flip-left">
          <div class="text">Let's Get in Touch</div>
          <p class="paragraph-3">Interested in working together? We should queue up a chat. I’ll buy the coffee!!</p>
          <div class="icons">
            <div class="row">
              <i class="fas fa-user"></i>
              <div class="info">
                <div class="head">Name</div>
                <div class="sub-title">TEJAS THAWARI</div>
              </div>
            </div>
            <div class="row">
              <i class="fas fa-map-marker-alt"></i>
              <div class="info">
                <div class="head">Address</div>
                <div class="sub-title">Alandi,Pune 412105.</div>
              </div>
            </div>
            <div class="row">
              <i class="fas fa-envelope"></i>
              <div class="info">
                <div class="head">Email</div>
                <div class="sub-title">Tejas.thawari2015@gmail.com</div>
              </div>
            </div>
          </div>
        </div>
        <div class="column right" data-aos="flip-right">
          <div class="text">
            Message Me
          </div>
          <form action="#Contact">
            <div class="fields">
              <div class="field name">
                <input type="text" id="fromName" placeholder="Name" required autocomplete="off">
              </div>
              <div class="field email">
                <input type="email" id="emailSender" placeholder="Email" required autocomplete="off">
              </div>
            </div>
            <div class="field">
              <input type="text" id="subjectSender" placeholder="Subject" required autocomplete="off">
            </div>
            <div class="field textarea">
              <textarea cols="30" rows="10" id="message" placeholder="Message" required autocomplete="off"></textarea>
            </div>
            <div class="button">
              <button onclick='sendMail()' type="submit">Send Message</button>
            </div>
          </form>
        </div>
      </div>
    </div>
  </section>
  <!-- footer section start -->
  <footer>
    <div class="text-center">
      <span>
        Created By <a href="#">TEJAS THAWARI</a> | <span class="far fa-copyright"> </span> <script>document.write(new Date().getFullYear())</script> All rights reserved.
        <div>
          <a href="https://in.linkedin.com/in/tejas-thawari"><i class="fab fa-linkedin"></i></a>
          <a href="https://github.com/tejasthawari4"><i class="fab fa-github"></i></a>
          <a href="https://www.tsthawari.blogspot.com/"><i class="fab fa-blogger"></i></a>
        </div>
      </span>
    </div>
  </footer>
  <script src="script.js"></script>
  <script>
    // When the user scrolls the page, execute myFunction 
    window.onscroll = function() {myFunction()};
    
    function myFunction() {
      var winScroll = document.body.scrollTop || document.documentElement.scrollTop;
      var height = document.documentElement.scrollHeight - document.documentElement.clientHeight;
      var scrolled = (winScroll / height) * 100;
      document.getElementById("myBar").style.width = scrolled + "%";
    }
    </script>
    <script src="https://unpkg.com/aos@next/dist/aos.js"></script>
    <script>AOS.init({easing : 'ease-in',delay: 100,duration: 300,offset:100});window.addEventListener('load', AOS.refresh);</script>
</body>

</html>
