# 🌌 Kunal Daharwal – Neon GitHub Profile

## 1) `README.md`

````md
<h1 align="center">Hi 👋, I'm Kunal Daharwal</h1>
<h3 align="center">Next.js | NestJS | MERN | Machine Learning Engineer</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?lines=Next.js+%26+NestJS+Developer;System+Design+%26+DSA+in+Java;DevOps+Learner;AI+%26+Web+Engineer;Building+Real+World+Products&center=true&width=650&height=50">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/kunal592/kunal592/output/github-contribution-grid-snake-dark.svg">
</p>

---

## 🧠 About Me (Glass Mode)

```diff
+ 🚀 Tech Focus: Next.js, NestJS, MERN
+ 🧩 Problem Solving: DSA in Java
+ 🏗 System Design & DBMS
+ ☁ DevOps: Docker, CI/CD, Cloud
+ 🤖 ML Engineer (Model → API → UI)
````

---

## ⚡ Tech Stack (Neon Grid)

### Frontend

![Next.js](https://img.shields.io/badge/Next.js-black?style=for-the-badge\&logo=next.js)
![React](https://img.shields.io/badge/React-00E5FF?style=for-the-badge\&logo=react)

### Backend

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge\&logo=nestjs)
![Node.js](https://img.shields.io/badge/Node.js-00FF7F?style=for-the-badge\&logo=node.js)
![Express](https://img.shields.io/badge/Express-111111?style=for-the-badge\&logo=express)

### DSA & Core

![Java](https://img.shields.io/badge/Java-FF6F00?style=for-the-badge\&logo=openjdk)
![C++](https://img.shields.io/badge/C%2B%2B-00CFFF?style=for-the-badge\&logo=cplusplus)

### DevOps & Cloud

![Docker](https://img.shields.io/badge/Docker-0db7ed?style=for-the-badge\&logo=docker)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge\&logo=github-actions)

---

## 📊 GitHub Stats (Neon Cards)

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=kunal592&show_icons=true&theme=tokyonight&hide_border=true" width="48%"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=kunal592&theme=tokyonight&hide_border=true" width="48%"/>
</p>

---

## 🔥 Top Languages

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kunal592&layout=compact&theme=tokyonight&hide_border=true"/>
</p>

---

## 🌐 Connect

<p align="center">
  <a href="https://www.linkedin.com/in/kunal-daharwal">
    <img src="https://img.shields.io/badge/LinkedIn-00CFFF?style=for-the-badge&logo=linkedin">
  </a>
  <a href="https://www.kdxlabs.cloud">
    <img src="https://img.shields.io/badge/Portfolio-9B5CFF?style=for-the-badge&logo=vercel">
  </a>
</p>

---

💎 *“Build clean. Scale fast. Ship often.”*

````

---

## 2) Animated Snake Setup

Create this file:

**`.github/workflows/snake.yml`**

```yml
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: kunal592
          outputs: |
            output/github-contribution-grid-snake.svg
            output/github-contribution-grid-snake-dark.svg

      - name: Push Snake
        uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: output
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
````

