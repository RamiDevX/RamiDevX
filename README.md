<div align="center">
name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:020b18,35:071d6b,65:1247d6,100:00d4ff&height=200&section=header&text=Rami%20Bitar&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=62&desc=Computer%20Programming%20Student%20%C2%B7%20Developer&descSize=16&descAlignY=78&descColor=a8d8ff&stroke=00d4ff&strokeWidth=1" width="100%"/>

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=RamiDevX&color=1a5eff&style=flat-square&label=Profile+Views)
&nbsp;&nbsp;
![Open to Internship](https://img.shields.io/badge/💼_Open_to-Internship-00d4ff?style=flat-square&labelColor=071d6b)

<br/><br/>

<img src="https://raw.githubusercontent.com/RamiDevX/RamiDevX/main/noorify-avatar.png" width="110"/>

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&pause=1000&color=00D4FF&center=true&vCenter=true&width=620&lines=Python+%26+Web+Developer+%F0%9F%90%8D;Telegram+Bot+Creator+%F0%9F%A4%96;Arduino+%26+Robotics+Enthusiast+%E2%9A%A1;Building+software+that+solves+real+problems+%F0%9F%9A%80)](https://git.io/typing-svg)

<br/>

> *"Code with purpose — every line is a chance to build something that matters."*

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:020b18,50:1247d6,100:00d4ff&height=2&section=header" width="100%"/>

## 👨‍💻 About Me

Computer Programming student passionate about building software that solves real problems.
My work spans **Python**, **JavaScript**, **HTML/CSS**, and embedded systems — from web applications to Arduino-powered robotics projects.

Currently open to **internship opportunities** to contribute to development teams and grow in real-world environments.

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00d4ff,50:1247d6,100:020b18&height=2&section=header" width="100%"/>

## 📚 Currently Learning

| Skill | Focus |
|-------|-------|
| 🌐 Flask / FastAPI | Building REST APIs with Python |
| 🗄️ MySQL & MongoDB | Database design & queries |
| 🐳 Docker | Containerization & deployment |
| ⚙️ GitHub Actions | CI/CD & workflow automation |

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:020b18,50:1247d6,100:00d4ff&height=2&section=header" width="100%"/>

## 🛠️ Skills

**Languages**

![Python](https://img.shields.io/badge/Python-020b18?style=for-the-badge&logo=python&logoColor=00d4ff)
![JavaScript](https://img.shields.io/badge/JavaScript-020b18?style=for-the-badge&logo=javascript&logoColor=00d4ff)
![HTML5](https://img.shields.io/badge/HTML5-020b18?style=for-the-badge&logo=html5&logoColor=00d4ff)
![CSS3](https://img.shields.io/badge/CSS3-020b18?style=for-the-badge&logo=css3&logoColor=00d4ff)

**Tools & APIs**

![Telegram Bot API](https://img.shields.io/badge/Telegram_Bot_API-020b18?style=for-the-badge&logo=telegram&logoColor=00d4ff)
![Git](https://img.shields.io/badge/Git-020b18?style=for-the-badge&logo=git&logoColor=00d4ff)
![GitHub](https://img.shields.io/badge/GitHub-020b18?style=for-the-badge&logo=github&logoColor=00d4ff)
![VS Code](https://img.shields.io/badge/VS_Code-020b18?style=for-the-badge&logo=visualstudiocode&logoColor=00d4ff)

**Hardware**

![Arduino](https://img.shields.io/badge/Arduino-020b18?style=for-the-badge&logo=arduino&logoColor=00d4ff)
![Robotics](https://img.shields.io/badge/Robotics-020b18?style=for-the-badge&logo=ros&logoColor=00d4ff)

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00d4ff,50:1247d6,100:020b18&height=2&section=header" width="100%"/>

## 🌟 Projects

### 🤖 NoorifyBot — صدقة جارية رقمية

<div align="center">

> ### ﴿ وَذَكِّرْ فَإِنَّ الذِّكْرَىٰ تَنفَعُ الْمُؤْمِنِينَ ﴾

**تذكير دوري بالأذكار للمجموعات والقنوات والأفراد**

A Telegram bot delivering scheduled Islamic dhikr reminders to groups, channels, and individuals.

[![Active Users](https://img.shields.io/badge/Active_Users-100%2B-1a5eff?style=for-the-badge)](https://t.me/Noorify_bot)
&nbsp;
[![Try NoorifyBot](https://img.shields.io/badge/Try_NoorifyBot-%E2%86%92-00d4ff?style=for-the-badge&logo=telegram&logoColor=020b18)](https://t.me/Noorify_bot)
&nbsp;
[![Source Code](https://img.shields.io/badge/Source_Code-020b18?style=for-the-badge&logo=github&logoColor=white)](https://github.com/RamiDevX/Noorify_Bot)

`Python` · `Telegram Bot API` · `Task Scheduling`

</div>

<br/>

### ⚙️ Automation Lab — مختبر الأتمتة

<div align="center">

A Telegram channel sharing automation tips, Python scripts, and development resources.

[![Visit Channel](https://img.shields.io/badge/Automation_Lab-%E2%86%92-1a5eff?style=for-the-badge&logo=telegram&logoColor=ffffff)](https://t.me/AutoLabOfficial)

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:020b18,50:1247d6,100:00d4ff&height=2&section=header" width="100%"/>

## 📊 GitHub Stats

<div align="center">

<img width="100%" src="https://streak-stats.demolab.com?user=RamiDevX&theme=transparent&background=020b18&border=1a5eff&stroke=1a5eff&ring=00d4ff&fire=00d4ff&currStreakLabel=00d4ff&sideLabels=7eb8ff&dates=7eb8ff&sideNums=ffffff&currStreakNum=ffffff"/>

<br/>

<img height="170" src="https://github-readme-stats.vercel.app/api?username=RamiDevX&show_icons=true&theme=transparent&title_color=00d4ff&text_color=ffffff&icon_color=1a5eff&border_color=1a5eff&bg_color=020b18"/>
&nbsp;&nbsp;
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=RamiDevX&layout=compact&theme=transparent&title_color=00d4ff&text_color=ffffff&border_color=1a5eff&bg_color=020b18"/>

<br/>

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=RamiDevX&bg_color=020b18&color=00d4ff&line=1a5eff&point=00d4ff&area=true&hide_border=false&border_color=1a5eff&area_color=071d6b"/>

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00d4ff,50:1247d6,100:020b18&height=2&section=header" width="100%"/>

## 🏆 Trophies

<div align="center">

<img width="100%" src="https://github-profile-trophy.vercel.app/?username=RamiDevX&theme=darkhub&no-frame=true&row=1&column=6&margin-w=4&margin-h=4"/>

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:020b18,50:1247d6,100:00d4ff&height=2&section=header" width="100%"/>

## 🐍 Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/RamiDevX/RamiDevX/output/github-contribution-grid-snake-dark.svg" width="100%"/>

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00d4ff,50:1247d6,100:020b18&height=2&section=header" width="100%"/>

## 📬 Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-020b18?style=for-the-badge&logo=linkedin&logoColor=00d4ff)](https://linkedin.com/in/rami-bitar-16479936b)
[![GitHub](https://img.shields.io/badge/GitHub-020b18?style=for-the-badge&logo=github&logoColor=00d4ff)](https://github.com/RamiDevX)
[![Telegram](https://img.shields.io/badge/Telegram-020b18?style=for-the-badge&logo=telegram&logoColor=00d4ff)](https://t.me/ramibitar)
[![X](https://img.shields.io/badge/X_(Twitter)-020b18?style=for-the-badge&logo=x&logoColor=00d4ff)](https://x.com/RamiBitar_dev)
[![Instagram](https://img.shields.io/badge/Instagram-020b18?style=for-the-badge&logo=instagram&logoColor=00d4ff)](https://www.instagram.com/ramibitarr)
[![Facebook](https://img.shields.io/badge/Facebook-020b18?style=for-the-badge&logo=facebook&logoColor=00d4ff)](https://www.facebook.com/share/1CJPw8tjwy/)
[![Email](https://img.shields.io/badge/Email-020b18?style=for-the-badge&logo=gmail&logoColor=00d4ff)](mailto:ramibitar.connct@gmail.com)
[![Linktree](https://img.shields.io/badge/Linktree-020b18?style=for-the-badge&logo=linktree&logoColor=00d4ff)](https://linktr.ee/ramibitarr)

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00d4ff,35:1247d6,65:071d6b,100:020b18&height=160&section=footer&reversal=true" width="100%"/>

</div>
