<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=ChunkFive+Ex&weight=500&size=30&pause=1000&color=FFFFFF&center=true&vCenter=true&width=435&lines=Welcome+to+My+Profile!+%F0%9F%A4%A7+"alt=Typing SVG">
  </a>
</div> 

## 

<div align="center">
  <p>Sou estudante de Desenvolvimento de Sistemas no SESI/SENAI, com interesse em programação, desenvolvimento web e tecnologia. Atualmente estudo Java, lógica de programação, banco de dados e desenvolvimento de aplicações, buscando constantemente aprimorar minhas habilidades por meio de projetos e aprendizado contínuo. Estou aberto a oportunidades de estágio, networking e novos desafios na área de tecnologia.</p>
</div>

##

<h3 align="left">Social Medias</h3>
<div> 
  <a href="https://www.linkedin.com/in/enzo-wakida/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
  <a href="https://www.instagram.com/enzowakida" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
  <a href="https://steamcommunity.com/id/StupidSapper" target="_blank"><img src="https://img.shields.io/badge/Steam-000000?style=for-the-badge&logo=steam&logoColor=white" target="_blank"></a>

</div>

##

<div style="text-align: center;" align="center">
  <h3>--- GitHub Stats ---</h3>
  <br>

  <div style="display: flex; justify-content: center; gap: 30px;">
    <img src="https://github-stats-extended.vercel.app/api?username=enzowakida&show_icons=true&theme=dark&rank_icon=github" style="height: 160px;" />
    <img src="https://github-stats-extended.vercel.app/api/top-langs/?username=enzowakida&layout=compact&theme=dark" style="height: 160px;" />
  </div>

  - uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.enzowakida }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:           A preset of color, one of [github, github-dark, github-light]
    #  - color_snake:       Color of the snake
    #  - color_dots:        Coma separated list of dots color.
    #                       The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                       Exactly 5 colors are expected.
    #  - color_background:  Color of the background (for gif only)
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9&color_background=#aaaaaa
