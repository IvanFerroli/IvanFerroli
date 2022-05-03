### Hi! I'm Ivanilson Ferreira, a brazilian design student who decided to change careers.

- 👨‍🎓️ I’m currently studying to become a full-stack developer. HTML / CSS / JavaScript (Vanilla, Node Js, React Js) / MySQL / MongoDb
- 🙃️ Pronouns: EN: he/him PT-BR: ele/dele



<div>
  <a href="https://github.com/IvanFerroli">
  <img height="160em" src="https://github-readme-stats.vercel.app/api?username=IvanFerroli&theme=highcontrast"/>
  <img height="160em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=IvanFerroli&layout=compact&theme=highcontrast"/>
</div>
  
<div style="display: inline_block"><br>
  <img align="center" alt="Ivan-React" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" />
  <img align="center" alt="Ivan-Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
  <img align="center" alt="Ivan-HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="Ivan-CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
  <img align="center" alt="Ivan-CSharp" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg">
  <img align="center" alt="Ivan-Node" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg">
  <img align="center" alt="Ivan-Node" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original-wordmark.svg"> 
</div>
  
  ##
  
  <div>
    <a href="https://www.linkedin.com/in/ivanilson-ferreira/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
    <a href = "mailto:ivanilson.ferreira.mec@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  </div>
  - uses: Platane/snk@v2
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
