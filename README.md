  <style>
    @import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600;700&display=swap');

    .main {
      height: 250px;
      position: relative;
    }

    .title {
      display: flex;
      justify-content: center;
      align-items: center;
      font-family: 'Open Sans';
      padding: 32px;
      margin: 0px;
      position: absolute;
      top: 0; left: 0; bottom: 0; right: 0;
      text-align: center;
      animation-duration: 0s;
      animation-fill-mode: both;
    }

    .title1 {
      opacity: 1;
      animation-name: title1animation ;
      animation-delay: 1.6s;
    }

    @keyframes title1animation {
      100% {
        opacity: 0;
      }
    }

    .title2 {
      opacity: 0;
      animation-name: title2animation;
      animation-delay: 1.6s;
    }

    @keyframes title2animation {
      100% {
        opacity: 1;
      }
    }

    .animatedBox {
      height: 100%;
      width: 0px;
      left: 0;
      position: absolute;
      animation-name: boxAnimation;
      animation-fill-mode: both;
    }

    .animatedBox1 {
      background-color: black;
      animation-duration: 1.2s;
      animation-delay: 1s;
    }

    .animatedBox2 {
      background-color: #cc1355;
      animation-duration: 1s;
      animation-delay: 1.1s;
    }

    @keyframes boxAnimation {
      0% {
        width: 0.5%;
        left: 0px;
        right: unset;
      }
      49.999% {
        left: 0px;
        right: unset;
      }
      50% {
        width: 100%;
        left: unset;
        right: 0px;
      }
      100% {
        width: 0.5%;
        left: unset;
        right: 0px;
      }
    }
  </style>
  
  <main class="main">
    <h1 class="title title1">Hi there 👋, I'm Mathis Barré</h1>
    <h1 class="title title2">A front-end web developer <br> mainly working with React.js</h1>
    <!-- <h1 class="title" id="h1-3">A french web developer</h1> -->
    <div class="animatedBox animatedBox1"></div>
    <div class="animatedBox animatedBox2"></div>
  </main>

### Hi there 👋

- 🔭 I’m currently working on developerssources.now.sh, a website to find good learning sources as beginner developer 
- 🌱 I’m currently learning Javascript and SVG animations & professional React and Gatsby stuff
- 📫 Reach me on mathisbarre.com
- 🇫🇷 Currently available for hire on Angers or Nantes in France

### My history

I started programming at the age of 10 but it's during my junior high school years and until the equivalent of 10th grade in france that this passion was imposed thanks to several logic and algorithmic python contests. It's also at this time that I started integrating web pages in HTML/CSS thanks to codecademy, OpenClassroom and Grafikart courses.

From 11th grade (France equivalent), I decided to do the distance learning courses in order to devote more time to sports and web development. This decision led me to get my high school diploma but also and above all an advanced knowledge in responsive integration and Javascript ES6 then in React, Sass, Gatsby, NextJs, GreenShock, Git, Github, AdobeXD, Jekyll, NodeJs, ExpressJs, MongoDB thanks to Freecodecamp.org, a lot of documentations and a lot of small and big projects.

After that, I created my own business in early 2020 in order to get some freelance missions.
My next goal is to get a job in a company in order to improve my programming skills but also to learn teamwork and its requirements!
