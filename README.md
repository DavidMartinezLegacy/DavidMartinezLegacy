## Hi there 👋
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=OogwayLeonardo)](https://github.com/anuraghazra/github-readme-stats)
### Hi there 👋 This is Johnny ！✨ 
 
 
[![Github](https://img.shields.io/badge/-Github-000?style=flat&logo=Github&logoColor=white)](https://github.com/zhanglina94)
[![Linkedin](https://img.shields.io/badge/-LinkedIn-blue?style=flat&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/lina-zhang-58440b101/)
[![Gmail](https://img.shields.io/badge/-Gmail-c14438?style=flat&logo=Gmail&logoColor=white)](zhanglina249@gmail.com)
 
Welcome to my Github page! I am Lina and I am currently Learning NLP and RL!  
 
<img align="right" alt="img" src="https://github.com/zhanglina94/zhanglina94/blob/main/img/pic.jpg" width="50%" height="auto" />
 
 
#### 🌱 Things I am currently working on 🌱 : 
- Taking online courses about Data Science and Machine Learning 
- [My website](https://OogwayLeonardo.github.io) 🚀 *coming soon*
 
 
#### ⚡ Things recent ones I'm interested in ⚡ : 
- Chat GPT
- Stable Diffusion
- Image generation
- Layout2image
- pix2pix
#### 🌻 I am studying 🌻
- IELTS
- French
- German
#### :computer: Programming languages and tools :computer: : 
<p>
<img width="50%" align="right" src="https://github-readme-stats.vercel.app/api?username=zhanglina94&show_icons=true&hide_border=true" />
<code><img width="10%" src="https://www.vectorlogo.zone/logos/ubuntu/ubuntu-ar21.svg"></code>
<code><img width="10%" src="https://www.vectorlogo.zone/logos/python/python-ar21.svg"></code>
<code><img width="10%" src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-ar21.svg"></code>
<br />
<code><img width="10%" src="https://www.vectorlogo.zone/logos/git-scm/git-scm-ar21.svg"></code>
<code><img width="10%" src="https://www.vectorlogo.zone/logos/virtualbox/virtualbox-ar21.svg"></code>
<code><img width="10%" src="https://www.vectorlogo.zone/logos/visualstudio_code/visualstudio_code-ar21.svg"></code>
<br />
<code><img width="10%" src="https://www.vectorlogo.zone/logos/reactjs/reactjs-ar21.svg"></code>
<code><img width="10%" src="https://commons.wikimedia.org/wiki/File:NXP_Semiconductors_logo_2023.svg"></code>
<code><img width="10%" src="https://www.vectorlogo.zone/logos/broccolijs/broccolijs-ar21.svg"></code>
</p>
<sub>Credits to: <br/>[Stable Diffusion](https://stablediffusionweb.com) for the wonderfull [picture](https://github.com/zhanglina94/zhanglina94/img/pic.jpg)</sub>
If you want to know more, please refer to the my [website](https://zhanglina94.github.io).
name: GitHub-Profile-3D-Contrib

on:
  schedule: # 02:30 IST == 21:00 UTC
    - cron: "0 21 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    name: generate-github-profile-3d-contrib
    steps:
      - uses: actions/checkout@v2
      - uses: yoshi389111/github-profile-3d-contrib@0.7.0
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
          USERNAME: ${{ github.repository_owner }}
      - name: Commit & Push
        run: |
          git config user.name github-actions
          git config user.email github-actions@github.com
          git add -A .
          git commit -m "generated"
          git push


<!--
**OogwayLeonardo/OogwayLeonardo** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
