![banner](HiBanner.svg)

<div align="center">
    <img src="https://img.shields.io/badge/badges-awesome-green.svg" alt="Java">
    <br>
    <br>
    <p>Hello, my name is Gian Marco. Currently, I am studying Systems and Informatics Engineering. I am passionate about all topics            related to technology, and I enjoy constantly learning new things. I have worked on personal web development projects and                intermediate-level university projects. In these projects, I have used technologies such as JavaScript, Vue.js, Java, JavaFX, and        Java Swing. Additionally, I have a keen interest in user experience (UX/UI) related aspects.</p>
</div>

<h2 align="center">Contact</h2>
<div align="center">
    <a href="https://www.linkedin.com/in/gian-marco-mora-tami-66233b20a/" target="blank" title="Gian Marco Mora Tami"><img                   align="center" src="inIcon.svg" alt="" height="40" width="40" /></a>
    &nbsp;&nbsp;&nbsp;
    <a href="https://discord.com/users/Gian%20Marco#1137" target="blank" title="Gian Marco#1137"><img align="center"                         src="discordIcon.svg" alt="" height="40" width="40" /></a>
    &nbsp;&nbsp;&nbsp;
    <a href="mailto:moragian6@gmail.com" target="blank" title="moragian6@gmail.com"><img align="center" src="gmailIcon.svg" alt=""           height="35" width="40"/></a>
    <br>
    <br>
</div>

<h2 align="center">Technology Stack</h2>
<div align="center">
  <img src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"                 alt="JavaScript">
  <img src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap">
  <img src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white" alt="NodeJS">
  <img src="https://img.shields.io/badge/vuejs-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D" alt="Vue.js">
  <img src="https://img.shields.io/badge/Adobe%20XD-470137?style=for-the-badge&logo=Adobe%20XD&logoColor=#FF61F6" alt="Adobe XD">
  <img src="https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white" alt="Figma">
</div>

- uses: gianmt-06/snk@v2
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
