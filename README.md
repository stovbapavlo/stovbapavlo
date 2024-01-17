
<div align="center">
  <h1 >Hi there, I'm Pavlo <img src="https://github.com/blackcater/blackcater/raw/main/images/Hi.gif" height="32"/></h1>
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=22&pause=1000&color=E2F7EE&center=true&vCenter=true&random=false&width=435&lines=I`m+Frontend+student" alt="Typing SVG" />
  </a>
</div>



<a href="https://git.io/streak-stats"><img src="https://github-readme-streak-stats.herokuapp.com?user=stovbapavlo&theme=graywhite&border_radius=4.6&card_width=1000" alt="GitHub Streak" /></a>

<!--
<div style="display: flex; justify-content: center;">
  <img src="https://github-readme-stats.vercel.app/api?username=stovbapavlo&show_icons=true&theme=graywhite" alt="GitHub Stats">
</div>
-->

<div align="center">
  <h3> How language i know</h3>
   <img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E" alt="JavaScript Badge">
  <img src="https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white" alt="C# Badge">
  <img src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3 Badge">
  <img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5 Badge">
  
  <div>
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=stovbapavlo&layout=compact" alt="Top Languages">
  </div>


<div align = "center">
  <h3>My leetcode</h3>
  <a href="https://github.com/KnlnKS/leetcode-stats">
    <img src="https://leetcode-stats-six.vercel.app/api?username=stovbapavlo" alt="KnlnKS's LeetCode Stats">
  </a>
</div>

- uses: Platane/stovbapavlo
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
