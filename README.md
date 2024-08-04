<h1 align="center">Hi 👋, I'm Yeasin Miah</h1>
<h3 align="center">Frontend Developer | React.js</h3>
<img src="https://i.ibb.co/R9t9Xty/Blue-Green-and-White-Modern-Tech-Web-Developer-Linked-In-Banner.png" alt="img">

<p align="left"> <img src="https://komarev.com/ghpvc/?username=yeasinmiah1272001&label=Profile%20views&color=0e75b6&style=flat" alt="yeasinmiah1272001" /> </p>

<div align="center">
  <p id="typewriter"></p>
</div>

<script>
  const words = ["Frontend Developer", "React.js Enthusiast", "Learning Next.js and TypeScript"];
  let i = 0;
  let timer;

  function typingEffect() {
    let word = words[i].split("");
    var loopTyping = function () {
      if (word.length > 0) {
        document.getElementById('typewriter').innerHTML += word.shift();
      } else {
        deletingEffect();
        return false;
      };
      timer = setTimeout(loopTyping, 200);
    };
    loopTyping();
  };

  function deletingEffect() {
    let word = words[i].split("");
    var loopDeleting = function () {
      if (word.length > 0) {
        word.pop();
        document.getElementById('typewriter').innerHTML = word.join("");
      } else {
        if (words.length > (i + 1)) {
          i++;
        } else {
          i = 0;
        };
        typingEffect();
        return false;
      };
      timer = setTimeout(loopDeleting, 100);
    };
    loopDeleting();
  };

  typingEffect();
</script>

- 🔭 I’m currently working on [Book-store](https://fretful-temper.surge.sh/)

- 🌱 I’m currently learning **react.js, Next.js, TypeScript**

- 👨‍💻 All of my projects are available at [https://yeasin-portfolio-website.vercel.app/](https://yeasin-portfolio-website.vercel.app/)

- 📫 How to reach me **yeasinmiah1272001@gmail.com**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/https://www.linkedin.com/in/yeasin-miah-198b5829a/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="https://www.linkedin.com/in/yeasin-miah-198b5829a/" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> 
  <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> 
  </a> 
  <a href="https://www.figma.com/" target="_blank" rel="noreferrer"> 
    <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/> 
  </a> 
  <a href="https://firebase.google.com/" target="_blank" rel="noreferrer"> 
    <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="40" height="40"/> 
  </a> 
  <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> 
  </a> 
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> 
  </a> 
  <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> 
  </a> 
  <a href="https://nodejs.org" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> 
  </a> 
  <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> 
  </a> 
  <a href="https://reactnative.dev/" target="_blank" rel="noreferrer"> 
    <img src="https://reactnative.dev/img/header_logo.svg" alt="reactnative" width="40" height="40"/> 
  </a> 
  <a href="https://tailwindcss.com/" target="_blank" rel="noreferrer"> 
    <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="tailwind" width="40" height="40"/> 
  </a> 
  <a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/> 
  </a> 
</p>

<p><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=yeasinmiah1272001&show_icons=true&locale=en&layout=compact" alt="yeasinmiah1272001" /></p>
