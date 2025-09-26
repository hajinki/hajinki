# 👋 Hi there, I'm Hajin

## 🚀 Tech Stack
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-0095D5?style=for-the-badge&logo=kotlin&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)

## 📊 GitHub Stats
![Hajin's GitHub stats](https://github-readme-stats.vercel.app/api?username=hajinki&show_icons=true&theme=tokyonight)
![GitHub Streak](https://streak-stats.demolab.com/?user=hajinki&theme=tokyonight)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=hajinki&layout=compact&theme=tokyonight)

name: GitHub-Profile-Summary-Cards

on:
  schedule:
    - cron: '0 0 * * *'   # 매일 00:00 UTC 한 번
  workflow_dispatch:

permissions:
  contents: write

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4

      - name: Generate summary cards
        uses: vn7n24fzkq/github-profile-summary-cards@release
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
        with:
          USERNAME: hajinki            # 본인 username 명시
          # EXCLUDE: "pull_request"    # 원하면 제외 타입 지정 가능
          # BRANCH: "main"             # 기본 브랜치 다르면 지정
          # UTC_OFFSET: "+09:00"       # 한국시간 반영하고 싶으면









- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

