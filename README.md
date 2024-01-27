<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="biodata.css" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css" />
    <title>Personal Portofolio</title>
  </head>
  <body>
    <header>
      <nav class="navigasi">
        <!--untuk responsif-->
        <input type="checkbox" id="btn-responsive" hidden />
        <label for="btn-responsive" class="btn-responsive">
          <span class="bar"></span>
          <span class="bar"></span>
          <span class="bar"></span>
        </label>
        <!--untuk responsif-->
        <ul class="head">
          <li><a href="#contact">Contact</a></li>
          <li><a href="#skill">Skill</a></li>
          <li><a href="#">About me</a></li>
        </ul>
      </nav>
    </header>
    <div class="container">
      <div class="header">
        <div class="header-text">
          <h1>Programmer & Developer</h1>
          <h2>Hello, I'm Sintya</h2>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Omnis, facilis? Lorem ipsum dolor sit, amet consectetur adipisicing. Lorem ipsum dolor sit amet consectetur adipisicing elit. Sed hic vel aperiam neque dolorem doloremque
            beatae similique fugit, autem distinctio.
          </p>
        </div>
      </div>
      <div class="utama">
        <div class="main top">
          <div class="top-text">
            <p><span class="fa fa-users"></span>Mufarikhatus Sintya</p>
            <p><span class="fa fa-map-marker"></span>Jepara, Jawa Tengah, Indonesia</p>
            <p id="skill"><span class="fa fa-graduation-cap"></span> Universitas Islam Nahdlatul Ulama Jepara</p>
          </div>
          <div class="garis">
            <hr />
          </div>
        </div>
        <div class="main skill">
          <div class="mid-text">
            <h1>Skill</h1>
            <div class="point">
              <div class="javascript">
                <p>Javascript</p>
                <div class="pin satu">70%</div>
                <div class="end"></div>
              </div>
              <div class="html">
                <p>html</p>
                <div class="pin dua">70%</div>
                <div class="end"></div>
              </div>
              <div class="python">
                <p>python</p>
                <div class="pin tiga">70%</div>
                <div class="end"></div>
              </div>
            </div>
          </div>
          <div class="garis">
            <hr />
          </div>
        </div>
        <div id="contact" class="main contact">
          <div class="end-text">
            <h1>Contact</h1>
            <div class="fa-contact">
              <!-- fa-2x utnuk memperbesar 2 kali-->
              <a href="#"><span class="fa fa-phone"></span>089507111682</a>
              <a href="#"><span class="fa fa-envelope-o"></span>mufasintya@gamil.com</a>
              <a href="#"><span class="fa fa-linkedin"></span>mufasintya</a>
              <a href="#"><span class="fa fa-instagram"></span>@sintyaast</a>
            </div>
          </div>
        </div>
        <div class="footer">
          <div class="footer-main">
            <p class="contoh">Find me on social media</p>
            <span class="fa fa-instagram"></span><span class="fa fa-twitter-square"></span><span class="fa fa-facebook-square"></span><span class="fa fa-linkedin-square"></span><span class="fa fa-pinterest-square"></span>
            <p class="contoh-2">Thank You</p>
          </div>
        </div>
      </div>
    </div>
  </body>
</html>
