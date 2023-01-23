
👋 Merhaba, Ben **Aydın Yağız**
- 👀 Web Uygulamaları geliştiriyorum.
- 🌱 Php, Laravel, C#, .Net ile ilgileniyorum.



<!--
**aydinyagizz/aydinyagizz** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->


##


![Github stats 1](https://github-readme-stats.vercel.app/api?username=aydinyagizz&show_icons=true&theme=gradient) 

##

  <div>   
<a href="https://www.linkedin.com/in/aydin-yagiz/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&lo-goColor=white" target="_blank"></a>   
</div>

##

[![GitHub Game of Life](https://github4life.herokuapp.com/aydinyagizz.gif?z=6)](https://github4life.herokuapp.com/aydinyagizz)

  
  
  
  name: Generate Datas

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"
  workflow_dispatch:

jobs:
  build:
    name: Jobs to update datas
    runs-on: ubuntu-latest
    steps:
      # Snake Animation
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: aydinyagizz
          svg_out_path: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
  ![Snake animation](https://github.com/aydinyagizz/aydinyagizz/blob/output/github-contribution-grid-snake.svg)
  
