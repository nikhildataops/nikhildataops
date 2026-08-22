<div align="center">

<!-- Animated gradient header banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=220&section=header&text=Hi%20There,%20I'm%20Nikhil%20Yadav%20👋&fontSize=35&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Aspiring%20Full%20Stack%20Developer%20|%20Node.js%20•%20Express.js%20•%20React.js&descAlignY=55&descSize=18" width="100%"/>

<!-- Typing animation -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=800&color=00F7FF&center=true&vCenter=true&width=650&lines=Full+Stack+Developer+in+Progress+%F0%9F%9A%80;Node.js+%2B+Express.js+%2B+React.js;Future+AI+%2F+ML+Explorer+%F0%9F%A4%96;DSA+with+Java+%F0%9F%92%BB;2nd+Year+CS+Student+%F0%9F%8E%93" alt="Typing SVG" />
</a>

</div>

<br/>

<h3 align="center">🧑‍💻 About Me</h3>

<p align="center">
🎓 2nd Year Student, based in <b>Bareilly, Uttar Pradesh, India</b> 🇮🇳<br/>
🌱 Currently building strong foundations in <b>Full Stack Development</b><br/>
🔭 Working with <b>Node.js</b>, <b>Express.js</b> &amp; <b>React.js</b><br/>
🧠 Practicing <b>DSA with Java</b><br/>
🚀 Exploring <b>MongoDB</b> and diving deeper into <b>React.js</b><br/>
🤖 Future goal: dive into <b>Artificial Intelligence</b><br/>
📫 Reach me at <b>yadavnikhil97616@gmail.com</b>
</p>

<br/>

<h3 align="center">🌐 Connect With Me</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/nikhildataops" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:yadavnikhil97616@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/nikhildataops" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

<br/>

<h3 align="center">🛠️ Tech Stack</h3>

<p align="center"><i>Languages &amp; tools I already know</i></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=c,html,css,js,java,python,mysql" />
</p>

<p align="center"><i>Currently learning</i></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=mongodb,react,nodejs,express" />
</p>

<br/>

<h3 align="center">📊 GitHub Stats</h3>

<p align="center">
  <img src="https://raw.githubusercontent.com/nikhildataops/nikhildataops/main/github-metrics.svg" width="90%"/>
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=nikhildataops&theme=darkhub&no-frame=true&row=1&column=6" />
</p>

<br/>

<h3 align="center">📈 Contribution Graph</h3>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=nikhildataops&theme=react-dark&hide_border=true&bg_color=0D1117&color=00F7FF&line=00F7FF&point=ffffff" width="90%"/>
</p>

<br/>

<!-- Snake contribution animation (background animation) -->
<h3 align="center">🐍 Contribution Snake</h3>
<p align="center">
  <img src="https://raw.githubusercontent.com/nikhildataops/nikhildataops/output/github-contribution-grid-snake-dark.svg" width="90%"/>
</p>

<blockquote align="center">
The snake animation above requires a one-time GitHub Actions setup — instructions are in the "Setup Guide" section below.
</blockquote>

<br/>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=nikhildataops&label=Profile%20Views&color=00F7FF&style=for-the-badge" />
</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer" width="100%"/>

---

## ⚙️ Setup Guide (for you, Nikhil — remove this section once done)

1. **Create the repo**: Make a new GitHub repo named exactly `nikhildataops` (must match your username) and add this file as `README.md`. This makes it your special profile README.

2. **Enable the Snake Animation** (the "🐍 Contribution Snake" section above):
   - In your `nikhildataops` repo, create a new file `.github/workflows/snake.yml` with this content:
     ```yaml
     name: Generate Snake
     on:
       schedule:
         - cron: "0 0 * * *"
       workflow_dispatch:
       push:
         branches: [ main ]

     jobs:
       generate:
         runs-on: ubuntu-latest
         permissions:
           contents: write
         steps:
           - uses: Platane/snk/svg-only@v3
             with:
               github_user_name: nikhildataops
               outputs: |
                 dist/github-contribution-grid-snake-dark.svg?palette=github-dark
           - uses: crazy-max/ghaction-github-pages@v4
             with:
               target_branch: output
               build_dir: dist
             env:
               GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
     ```
   - Push it, then run the workflow once manually from the **Actions** tab. It will auto-generate the snake SVG.

3. **Enable the GitHub Stats card** (self-hosted, same technique as the snake):
   - Create `.github/workflows/metrics.yml` in your repo with this content:
     ```yaml
     name: Metrics
     on:
       schedule:
         - cron: "0 0 * * *"
       workflow_dispatch:
       push:
         branches: [ main ]

     jobs:
       metrics:
         runs-on: ubuntu-latest
         permissions:
           contents: write
         steps:
           - uses: lowlighter/metrics@latest
             with:
               filename: github-metrics.svg
               token: ${{ secrets.GITHUB_TOKEN }}
               user: nikhildataops
               template: classic
               base: header, activity, community, repositories, metadata
               config_timezone: Asia/Kolkata
               plugin_languages: yes
               plugin_languages_analysis_timeout: 15
     ```
