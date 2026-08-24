<div align="center">

<!-- HERO -->

<img src="https://raw.githubusercontent.com/AanandAB/AanandAB/main/assets/hero.gif" width="100%" alt="Animated developer banner" />

<h1>Hey, I'm Aanand AB <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="32"></h1>

<p>
  <strong>Salesforce Developer · Full-Stack Builder · AI & Web3 Explorer</strong><br/>
  <sub>Kerala, India 🇮🇳 · Building products, systems and ideas that ship.</sub>
</p>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=18&duration=2600&pause=900&color=00FFD1&center=true&vCenter=true&width=780&lines=Salesforce+Developer+%E2%9A%A1+Full-Stack+Builder;Flutter+%C2%B7+React+%C2%B7+Solidity+%C2%B7+AI+Agents;Building+AIOS+v2.0+%E2%80%94+AI+that+is+the+OS;Turning+ideas+into+products%2C+one+commit+at+a+time." alt="Typing SVG" />

<br/><br/>

<a href="https://github.com/AanandAB"><img src="https://img.shields.io/github/followers/AanandAB?label=Followers&style=for-the-badge&color=00FFD1&labelColor=050A0E" /></a>
<a href="https://github.com/AanandAB"><img src="https://komarev.com/ghpvc/?username=AanandAB&style=for-the-badge&color=00FFD1&label=PROFILE+VIEWS" /></a>

</div>

> whoami

name: Aanand AB
role: Salesforce Developer & Full-Stack Builder
location: Kerala, India
currently_building: AIOS v2.0
interests:
  - AI Agents
  - Salesforce Development
  - Flutter
  - React
  - Web3 & Solidity
mindset: "Build it. Ship it. Improve it."

I enjoy building complete digital products—from polished interfaces and mobile apps to AI-powered systems, Salesforce integrations and decentralized applications.

⚡ Tech Arsenal

<div align="center">

Languages

<img src="https://skillicons.dev/icons?i=js,ts,dart,python,java,solidity,html,css&theme=dark" />

Frameworks & Platforms

<img src="https://skillicons.dev/icons?i=flutter,react,nodejs,vite,tailwind,electron,salesforce&theme=dark" />

Tools & Infrastructure

<img src="https://skillicons.dev/icons?i=git,github,firebase,postgres,mysql,docker,figma,ps&theme=dark" />

</div>

🚀 Featured Builds

<table>
<tr>
<td width="50%">

🤖 AIOS v2.0

An AI-first operating environment driven by local agents.

Multi-agent orchestration

Local AI experimentation

GUI vision and automation

Privacy-focused architecture

</td>
<td width="50%">

♟️ Knightly

A decentralized chess platform built as a blockchain-powered application.

Solidity smart contracts

On-chain game interactions

Trustless gameplay

Immutable match history

</td>
</tr>

<tr>
<td width="50%">

☕ CafePOSPro

A multi-platform point-of-sale ecosystem for cafés.

React + Electron desktop experience

Flutter mobile app

QR menu workflow

Real-time operations

</td>
<td width="50%">

🏢 Salesforce & Business Apps

Modern business workflows connected to powerful CRM systems.

Salesforce development

REST API integrations

Lead and workflow automation

Full-stack dashboards

</td>
</tr>
</table>

<div align="center">
  <sub>Explore more in my repositories ↓</sub>
</div>

📊 Contribution Universe

<div align="center">

<!-- MAIN ANIMATED CONTRIBUTION VISUAL -->

<img src="https://raw.githubusercontent.com/AanandAB/AanandAB/main/profile-3d-contrib/profile-night-rainbow.svg" width="100%" alt="3D contribution graph" />

<br/>

<!-- SNAKE ANIMATION -->

<img src="https://raw.githubusercontent.com/AanandAB/AanandAB/output/github-contribution-grid-snake-dark.svg" width="100%" alt="Snake animation eating contribution graph" />

</div>

🛰️ GitHub Telemetry

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=AanandAB&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=050A0E&title_color=00FFD1&icon_color=00FFD1&text_color=E8F4F2&rank_icon=github" />
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AanandAB&layout=compact&hide_border=true&bg_color=050A0E&title_color=00FFD1&text_color=E8F4F2" />

<br/><br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=AanandAB&hide_border=true&background=050A0E&ring=00FFD1&fire=FF6B6B&currStreakLabel=00FFD1&sideLabels=E8F4F2&dates=8CA7A5" />

<br/><br/>

<img src="https://github-profile-trophy.vercel.app/?username=AanandAB&theme=algolia&no-bg=true&no-frame=true&row=1&column=7&margin-w=8" width="100%" />

</div>

🧬 Activity Stream

<!--START_SECTION:activity-->

<!--END_SECTION:activity-->

Pro tip: Enable the GitHub Activity Readme workflow below to automatically populate this section with your latest public activity.

🌊 The Contribution Animation Stack

Your profile is designed around motion with purpose, not random decoration:

┌─────────────────────────────────────────────┐
│  HERO: typing animation                    │
│  ↓                                          │
│  CONTRIBUTIONS: animated 3D landscape       │
│  ↓                                          │
│  SNAKE: live contribution grid animation    │
│  ↓                                          │
│  STATS: streak + language + telemetry       │
│  ↓                                          │
│  TROPHIES: achievement showcase             │
│  ↓                                          │
│  ACTIVITY: latest GitHub actions            │
└─────────────────────────────────────────────┘

🛠️ Recommended GitHub Actions

1. 3D Contribution Graph

Create:

.github/workflows/profile-3d-contrib.yml

name: Generate 3D Contribution Graph

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    permissions:
      contents: write

    steps:
      - uses: actions/checkout@v4

      - uses: yoshi389111/github-profile-3d-contrib@0.7.1
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
        with:
          username: AanandAB

      - name: Commit generated files
        run: |
          git config user.name github-actions
          git config user.email github-actions@github.com
          git add .
          git commit -m "chore: update contribution graph" || exit 0
          git push

2. Contribution Snake Animation

Create:

.github/workflows/snake.yml

name: Generate Contribution Snake

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest
    permissions:
      contents: write

    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: AanandAB
          outputs: |
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

3. Latest GitHub Activity

Create:

.github/workflows/update-activity.yml

name: Update README with latest activity

on:
  schedule:
    - cron: "0 */6 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
      - uses: actions/checkout@v4

      - uses: jamesgeorge007/github-activity-readme@master
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

🌐 Connect With Me

<div align="center">

<a href="https://github.com/AanandAB">
  <img src="https://img.shields.io/badge/GitHub-AanandAB-050A0E?style=for-the-badge&logo=github&logoColor=00FFD1" />
</a>
<a href="https://linkedin.com/in/aanandab">
  <img src="https://img.shields.io/badge/LinkedIn-Aanand%20AB-050A0E?style=for-the-badge&logo=linkedin&logoColor=00FFD1" />
</a>
<a href="https://instagram.com/aanand_ab">
  <img src="https://img.shields.io/badge/Instagram-@aanand__ab-050A0E?style=for-the-badge&logo=instagram&logoColor=00FFD1" />
</a>

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=15&duration=3500&pause=1200&color=00FFD1&center=true&vCenter=true&width=700&lines=%3E+build+something+worth+committing.;%3E+ship+it.+learn.+repeat.;%3E+see+you+on+the+next+commit+%E2%9C%A6" alt="Closing message" />

</div>
