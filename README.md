# MyInternshipProjects
portfolio
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Pardeep - Developer Portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Poppins:wght@700&display=swap"
      rel="stylesheet"
    />
    <style>
      * {
        margin: 0;
        padding: 0;
      }
      body {
        background-color: rgb(0, 0, 33);
        color: white;
        font-family: "Poppins", sans-serif;
      }
      nav {
        display: flex;
        justify-content: space-around;
        align-items: center;
        height: 80px;
        background-color: rgb(18, 18, 62);
      }
      nav ul {
        display: flex;
        justify-content: center;
      }
      nav ul li {
        list-style: none;
        margin: 0 23px;
      }
      nav ul li a {
        text-decoration: none;
        color: white;
      }
      nav ul li a:hover {
        color: rgb(153, 153, 226);
        font-size: 1.02rem;
      }
      main hr {
        border: 0;
        background: #9c97f1;
        height: 1.2px;
        margin: 40px 84px;
      }
      .left {
        font-size: 1.5rem;
      }
      .First {
        display: flex;
        align-items: center;
        justify-content: space-around;
        margin: 13px 0;
      }
      .First > div {
        width: 40%;
      }
      .leftsection {
        font-size: 3rem;
      }
      .leftsection .button{
        padding:50px 0;
      }
      .leftsection .btn {
        padding: 12px;
        background:#1e2167;
        color: white;
        border-radius: 6px;
        font-size: 20px;
        cursor: pointer;
      }
      .leftsection .btn:hover{
        font-style: italic;
      }
      .rightsection img {
        width: 80%;
      }
      .purple {
        color: rgb(170, 107, 228);
      }
      .text-gray {
        color: gray;
      }
      #element {
        color: rgb(170, 107, 228);
      }
      .secondsection {
        max-width: 80vw;
        margin: auto;
        height: 80vh;
      }
      .secondsection h1 {
        font-size: 1.9rem;
      }
      .secondsection .box {
        background: white;
        width: 77vw;
        height: 2px;
        margin: 56px 0;
        display: flex;
      }
      .secondsection .vertical {
        height: 93px;
        width: 1px;
        background-color: white;
        margin: 0 120px;
      }
      .image-top{
        width: 23px;
        position: relative;
        top: -32px;
        left: -9px;
      }
      .vertical-title{
      position: relative;
      top: 75px;
      width: 150px;
      font-size: 14px;
      }
      .vertical-desc{
position: relative;
top: 86px;
color: gray;
width: 150px;
font-size: 9px;
      }
      footer{
        background-color: #0e0e1a;
      }
      .footer{
        display: flex;
        padding: 23px 122px;
        justify-content: space-evenly;
      }
      .footer ul{
        list-style: none;
      }

      .footer >div{
        width:223px ;
      }
      footer .footer-rights{
        text-align: center;
        color: gray;
        padding:12px 0;
      }
    </style>
  </head>
  <body>
    <header>
      <nav>
        <div class="left">Pardeep's Portfolio</div>
        <div class="right">
          <ul>
            <li><a href="/">Home</a></li>
            <li><a href="/">About</a></li>
            <li><a href="/">Services</a></li>
            <li><a href="/">Projects</a></li>
            <li><a href="/">Contact Me</a></li>
          </ul>
        </div>
      </nav>
    </header>
    <main>
      <section class="First">
        <div class="leftsection">
          Hi, My name is <span class="purple">Pardeep</span>
          <div>and I am a passionate</div>
          <span id="element"></span>
          <div class="buttons">
            <button class="btn">Downlad Resume</button>
            <button class="btn"> Visit Github</button>
          </div>
        </div>
        <div class="rightsection">
          <img src="web.png" alt="" />
        </div>
      </section>
      <hr />
      <section class="secondsection">
        <span class="text-gray">What I have done so far</span>
        <h1>Work Experience</h1>

        <div class="box">
          <div class="vertical">
            <img class="image-top" src="logo.png" alt="" />
            <div class="vertical-title">HTML Developer - Html </div>
            <div class="vertical-desc">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Expedita
              qui suscipit exercitationem earum, nulla cum esse molestiae iste
              quisquam eveniet natus?
            </div>
          </div>
          <div class="vertical">
            <img class="image-top" src="instagram.png" alt="" />
            <div class="vertical-title">CSS Developer -Instagram</div>
            <div class="vertical-desc">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Expedita
              qui suscipit exercitationem earum, nulla cum esse molestiae iste
              quisquam eveniet natus?
            </div>
          </div>
          <div class="vertical">
            <img class="image-top" src="twitter.png" alt="" />
            <div class="vertical-title">Javascript Developer - Twitter</div>
            <div class="vertical-desc">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Expedita
              qui suscipit exercitationem earum, nulla cum esse molestiae iste
              quisquam eveniet natus?
            </div>
          </div>
          <div class="vertical">
            <img class="image-top" src="Facebook.png" alt="" />
            <div class="vertical-title">Java Developer - Facebook</div>
            <div class="vertical-desc">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Expedita
              qui suscipit exercitationem earum, nulla cum esse molestiae iste
              quisquam eveniet natus?
            </div>
          </div>
          <div class="vertical">
            <img class="image-top" src="youtube.png" alt="" />
            <div class="vertical-title">Python Developer - Youtube</div>
            <div class="vertical-desc">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Expedita
              qui suscipit exercitationem earum, nulla cum esse molestiae iste
              quisquam eveniet natus?
            </div>
          </div>
          </div>
      </section>
    </main>
    <footer>
      <div class="footer">
        <div class=" footer-first">
          <h3>Pardeep's Developer Portfolio</h3>
        </div>
        <div class=" footer-second">
          <ul>
            <li>Home</li>
            <li>About</li>
            <li>Services</li>
            <li>Contact</li>
          </ul>
        </div>
        <div class=" footer-third">
          <ul>
            <li>Home</li>
            <li>About</li>
            <li>Services</li>
            <li>Contact</li>
          </ul>
        </div>
        <div class=" footer-fourth">
          <ul>
            <li>Home</li>
            <li>About</li>
            <li>Services</li>
            <li>Contact</li>
          </ul>
        </div>
      </div>
      <div class="footer-rights">
        Copyright &#169; pardeepsportfolio.com| All rights reserved
      </div>
    </footer>
    <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>

    <!-- Setup and start animation! -->
    <script>
      var typed = new Typed("#element", {
        strings: ["Java Devloper", "Web Developer", "software Developer"],
        typeSpeed: 50,
      });
    </script>
    <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>
  </body>
</html>
