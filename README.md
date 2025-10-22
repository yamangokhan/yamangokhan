# Merhaba! Ben Gökhan YAMAN 🚀

<p align="left">
  <a href="https://github.com/gokhanyaman">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=24&pause=1000&color=F70000&center=true&vCenter=true&width=450&lines=Software+Test+Automation+Engineer;Test+Otomasyonu+Stratejisti;Yaz%C4%B1l%C4%B1m+Kalitesi+Garanti+Alt%C4%B1nda!+QA+G%C3%BCc%C3%BC" alt="Typing SVG" />
  </a>
</p>

## Software Test Automation Engineer

<img align="right" alt="Coding" width="350" src="https://media.giphy.com/media/Q81N4g5y61m6c9gX18/giphy.gif">
<img align="right" alt="Coding" width="350" src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNTV0N2Q0ZjI5eTY5MXVkb2xrb2Q3NjA5cm0xYXR4YnNpMGJ0bDR1ZyZlcD12MV9pbnRlcm5hbF9naWYmY3Q9Zw/3oKIPnAiaS8EHzUjKw/giphy.gif">

### 🏆 GitHub Başarımlarım (Trophy)
<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=gokhanyaman&theme=onedark&no-frame=true&row=1&column=7" alt="GitHub Trophy" />
</p>

# .github/workflows/snake.yml
name: Generate Snake Animation

on:
  schedule:
    - cron: "0 0 * * *" # Her gün gece yarısı çalışır
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - uses: Platane/snk@v3
        with:
          github_user_name: gokhanyaman # KENDİ KULLANICI ADINIZI YAZIN
          outputs: |
            dist/github-snake.svg
            dist/github-snake-dark.svg?palette=github-dark
            dist/ocean.gif
            dist/solarized.gif
          # SVG'nin README.md'ye commit edilmesi
          commit_on_success: true
          git_branch: main
          repo_name: yamangokhan # KENDİ REPO ADINIZI YAZIN (Kullanıcı Adınız)

          ### 📈 GitHub İstatistiklerim
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=gokhanyaman&show_icons=true&theme=dark&include_all_commits=true&count_private=true" alt="GitHub İstatistikleri" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=gokhanyaman&layout=compact&theme=dark" alt="En Çok Kullanılan Diller" />
</p>
