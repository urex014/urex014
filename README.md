
    <script>
        function toggle(){
            document.body.classList.toggle("light");
            let theme = document.body.classList.contains("light")?"light":"dark";
            localStorage.setItem("theme",theme);
        }
        (function applySavedTheme(){
            let savedTheme = localStorage.getItem("theme");
            if(savedTheme==="light"){
                document.body.classList.add("light");
            }
        })();
    </script>


    <style>
        body{
            font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
            color: #ffff;
            display: flex;
            place-items: center;
            font-style: calc();
            justify-content: center;
            align-items:center;
            background-color: #131316;
        }
        body.light{
            background-color: white;
            color: #131316;
        }
        .container{
            border-radius: 8px;
            margin: 15px;
            background-image: linear-gradient( blueviolet,rgb(23, 1, 44));
            color: #ffff;
            box-shadow: 0 0 20px 10px  rgb(157, 68, 239);
            padding: 10px;
            padding-left: 15px;
        }
        img{
            margin: 15px;
        }
        h1{
            font-weight: 900;
        }
        a{
            text-decoration: none;
        }
        #change{
            border-radius:8px;
            margin: 15px;
            padding:16px;
            background-color: #ffff;
            width: fit-content;
            color:#131316;
            font-weight: bolder;
            cursor: pointer;
        }
        #change:hover{
            box-shadow: 0 0 20px rgb(228, 226, 231);
        }
    </style>
    <div class="container">
        <h1 align="center">Hi, I'm Amarachukwu Onuoha👋</h1>
        <h3 class="info" align="center">A Full-stack developer from Nigeria</h3>

        <p align="left"> <a href="https://twitter.com/amarachukwuonu4" target="blank"><img src="https://img.shields.io/twitter/follow/amarachukwuonu4?logo=twitter&style=for-the-badge" alt="amarachukwuonu4" /></a> </p>

    - 🌱 I’m currently learning **Express.js,gsap,react**

    - 👨‍💻 All of my projects are available at [https://amarachukwu.vercel.app/](https://amarachukwu.vercel.app/)

    - 📫 How to reach me **amarachukwuonuohabars007@gmail.com**

    <h3 align="left">Connect with me:</h3>
    <p align="left">
        <a href="https://twitter.com/amarachukwuonu4" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="amarachukwuonu4" height="30" width="40" /></a>
    </p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a> 
    <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a>
     <a href="https://expressjs.com" target="_blank" rel="noreferrer"> <img padding="15px" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="express" width="40" height="40"/> </a> 
     <a href="https://www.figma.com/" target="_blank" rel="noreferrer"> <img padding="15px" src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/> </a>
      <a href="https://firebase.google.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="40" height="40"/> </a> 
      <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a>
       <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a>
        <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> 
        <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a> 
        <a href="https://www.postgresql.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> </a> 
        <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> 
        <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a> 
        <a href="https://reactnative.dev/" target="_blank" rel="noreferrer"> <img src="https://reactnative.dev/img/header_logo.svg" alt="reactnative" width="40" height="40"/> </a> 
        <a href="https://tailwindcss.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="tailwind" width="40" height="40"/> </a> 
        <a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/> </a> </p>

<p><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=urex014&show_icons=true&locale=en&layout=compact" alt="urex014" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=urex014&" alt="urex014" /></p>
<div id="change" onclick="toggle()">Change theme</div>
    </div>
