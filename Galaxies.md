layout: page
title: "Galaxies"
permalink: /Portfolio

<!-- 
  Hello 😊.

  This template is designed and developed by Nisar Hassan Naqvi
  for anyone to use for free or customize the way they like.

  Github Repo: https://github.com/nisarhassan12/portfolio-template/
  My Website: https://nisar.dev

  For business & inquires, contact me => syednisarhassan12@gmail.com
-->

<!--
  Follow the instructions written in comments to create your stunning portfolio
-->

<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <link rel="shortcut icon" type="image/png" href="./images/kfavicon.png" />

  <!-- Put your site title here -->
  <title>
    Kelly Lavertu | A Data Scientist based in Atlanta, GA.
  </title>

  <meta name="description" content="Add small description of yourslef.">
  <!-- Add some coding keywords below, Ex: (React, CSS etc) -->
  <meta name="keywords" content="Kelly Lavertu - Data Scientist: Machine Learning, Artificial Intelligence, Deep Learning, Algorithm Development" />
  <link rel="stylesheet" href="index.css" />
</head>

<body>

  <!-- ***** Header ***** -->

  <header class="header" role="banner" id="top">
    <div class="row">
      <nav class="nav" role="navigation">
        <ul class="nav__items">
          <li class="nav__item"><a href="#portfolio" class="nav__link">Portfolio</a></li>
        <!--   <li class="nav__item"><a href="#about" class="nav__link">About Me</a></li> -->
          <li class="nav__item">
            <a href="#aboutme" class="nav__link">About Me</a>
          </li>
          <li class="nav__item">
            <a href="#contact" class="nav__link">Contact</a>
          </li>
        </ul>
      </nav>
    </div>
    <div class="header__text-box row">
      <div class="header__text">
        <h1 class="heading-primary">
          <!-- Replace the following name with your name -->
          <span>Kelly Lavertu</span>
        </h1>
        <!-- Put a small paragraph about yourself -->
        <p>Data Scientist located in Atlanta, GA</p>
        <a href="#contact" class="btn btn--pink">Get in touch</a>
      </div>
    </div>
  </header>

  <main role="main">

    <!-- ***** Portfolio ***** -->

    <section class="portfolio" id="portfolio">
      <div class="row">
        <h2>Portfolio</h2>
        <div class="work__boxes">

          <!-- Each div with the work__box class is a project. -->

          <div class="work__box">
            <div class="work__text">
              <h3>Advanced Classification Techniques for Galaxy, Quasar, and Star Identification</h3>
              <p>
                Utilized three different machine learning techniques and compared performance to each other, as well as previous attempts from different researchers.
              </p>
              <ul class="work__list">
                <li>Random Forest</li>
                <li>XGBoost</li>
                <li>Convolutional Neural Network</li>
              </ul>

              <div class="work__links">
                <a href="https://nisar.surge.sh" target="_blank" class="link__text">
                  Visit Project <span>&rarr;</span>
                </a>
                <a href="https://github.com/nisarhassan12/portfolio" title="View Source Code" target="_blank">
                  <img src="./images/github.svg" class="work__code" alt="GitHub">
                </a>
              </div>
            </div>
            <div class="work__image-box">
              <img src="./images/project-1.png" class="work__image" alt="Project 1" />
            </div>
          </div>

          <div class="work__box">
            <div class="work__text">
              <h3>Calculator</h3>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod,
                eius.
              </p>
              <ul class="work__list">
                <li>React</li>
                <li>Next.js</li>
                <li>Node</li>
                <li>MongoDB</li>
              </ul>

              <div class="work__links">
                <a href="#" class="link__text">
                  Visit Site <span>&rarr;</span>
                </a>
                <a href="#">
                  <img src="./images/github.svg" class="work__code" title="View Source Code" alt="GitHub">
                </a>
              </div>
            </div>
            <div class="work__image-box">
              <img src="./images/project-2.png" class="work__image" alt="Project 1" />
            </div>
          </div>

          <div class="work__box">
            <div class="work__text">
              <h3>Notificator</h3>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod,
                eius.
              </p>
              <ul class="work__list">
                <li>React</li>
                <li>Next.js</li>
                <li>Node</li>
                <li>MongoDB</li>
              </ul>

              <div class="work__links">
                <a href="#" class="link__text">
                  Visit Site <span>&rarr;</span>
                </a>
                <a href="#">
                  <img src="./images/github.svg" class="work__code" title="View Source Code" alt="GitHub">
                </a>
              </div>
            </div>
            <div class="work__image-box">
              <img src="./images/project-3.png" class="work__image" alt="Project 3" />
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- ***** Clients *****

    <section class="client" id="clients">
      <div class="row">
        <h2>Clients</h2>
        <div class="client__logos">
          Add logos of the clients or companies you'have worked with.
          <img src="./images/ronjones.png" class="client__logo" alt="Company 2" />
          <img src="./images/goldengrid.png" class="client__logo" alt="Company 3" />
          <img src="./images/bullseye.png" class="client__logo" alt="Company 1" />
          <img src="./images/mighty-furnitures.png" class="client__logo" alt="Company 1" />
          <img src="./images/fastlane.png" class="client__logo" alt="Company 3" />
          <img src="./images/chippy.png" class="client__logo" alt="Company 1" />
        </div>
      </div>
    </section>
//-->
    <!-- ***** About Me***** -->

    <section class="aboutme" id="aboutme">
      <div class="row">
        <h2>About Me</h2>
        <div class="about__content">
          <div class="about__text">
            <!-- Replace the below paragraph with info about yourself -->
            <p>
              For the past four years, I've had the privilege of serving as an AP Computer Science teacher at a high school in metro Atlanta. Beginning my journey as a STEM Resident at the Gwinnett School of Mathematics, Science, and Technology, I immersed myself in hands-on learning experiences and observed exemplary teaching methods. During this time, I obtained certifications in Mathematics and Computer Science 6-12, preparing me for a full-time teaching role at North Gwinnett High School. In my current capacity, I've adeptly guided students through the intricacies of the Java programming language, delving into advanced topics such as arrays, arraylists, recursion, and inheritance. Notably, my students have consistently surpassed national AP Exam pass rates by an impressive 40% over three years.​

              Prior to my teaching career, I honed my analytical and problem-solving skills as a programming analyst at a document distribution company. There, I took efforts to streamline document distribution processes, achieving a remarkable 90% reduction in manual processing time through the implementation of innovative technical solutions. My role also entailed the development of weekly prototypes tailored to meet client needs, facilitating prompt issue resolution and enhancing overall system performance. Finally, I gained invaluable experience in preparing and presenting detailed analyses, plans, and diagrams to a diverse audience, including both technical and non-technical stakeholders.
            </p>
            <!-- Provide a link to your resume -->
            <a href="#" class="btn">My Resume</a>
          </div>

          <div class="about__photo-container">
            <!-- Add a nice photo of yourself -->
            <img class="about__photo" src="./images/mastersgradphotocrop.jpg" alt="" />
          </div>
        </div>
      </div>
    </section>
  </main>

  <!-- ***** Contact ***** -->

  <section class="contact" id="contact">
    <div class="row">
      <h4>Get in Touch</h4>
<!--      <div class="contact__info">
        <p>
          Are you looking for a fast-performing and user-friendly website to
          represent your product or business? or looking for any kind of
          consultation? or want to ask questions? or have some advice for me
          or just want to say "Hi 👋" in any case feel free to Let me know. I
          will do my best to respond back. 😊 The quickest way to reach out to
          me is via an email.
        </p>
        Replace the email with yours 
        <a href="mailto:you@example.com" class="btn">you@example.com</a>
//-->
      </div>
    </div>
  </section>

  <!-- ***** Footer ***** -->

  <footer role="contentinfo" class="footer">
    <div class="row">
      <!-- Update the links to point to your accounts -->
      <ul class="footer__social-links">
        <li class="footer__social-link-item">
          <a href="mailto:kelly.lavertu@gmail.com" title="Link to Email">
            <img src="./images/gmailwhiteicon.png" class="footer__social-image" alt="Gmail">
          </a>
        </li>
        <li class="footer__social-link-item">
          <a href="https://github.com/klavertu/" title="Link to Github Profile">
            <img src="./images/github.svg" class="footer__social-image" alt="Github">
          </a>
        </li>
  <!--      <li class="footer__social-link-item">
          <a href="https://codepen.io/nisar_hassan" title="Link to Codepen Profile">
            <img src="./images/codepen.svg" class="footer__social-image" alt="Codepen">
          </a>
        </li>
     //-->   
        <li class="footer__social-link-item">
          <a href="https://www.linkedin.com/in/klavertu/">
            <img src="./images/linkedin.svg" title="Link to Linkedin Profile" class="footer__social-image" alt="Linkedin">
          </a>
        </li>
      </ul>

      <!-- If you give me some credit by keeping the below paragraph, will be huge for me 😊 Thanks. -->
      <p>
        &copy; 2024 - Template designed & developed by <a href="https://nisar.dev" class="link">Nisar</a>.
      </p>
      <div class="footer__github-buttons">
        <iframe
          src="https://ghbtns.com/github-btn.html?user=nisarhassan12&repo=portfolio-template&type=watch&count=true"
          frameborder="0" scrolling="0" width="170" height="20" title="Watch Portfolio Template on GitHub">
        </iframe>
      </div>
    </div>
  </footer>

  <a href="#top" class="back-to-top" title="Back to Top">
    <img src="./images/arrow-up.svg" alt="Back to Top" class="back-to-top__image"/>
  </a>
  <script src="./index.js"></script>
</body>

</html>