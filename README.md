### Hi there 👋

My name is **Danil Filatov**


- 🔭 I’m currently working on project for [*Yandex.Praktikum*](http://practicum.yandex.ru)
- 🌱 I’m currently learning JavaScript modules
- 📫 How to reach me:   
telegram - @MorganKatarn  
instagram - morgan_katarn

- 😄 Pronouns: Dude

[![Danil's GitHub stats](https://github-readme-stats.vercel.app/api?username=KaerMorgan&count_private=true&theme=radical)](https://github.com/anuraghazra/github-readme-stats)

<!--START_SECTION:waka-->
name: Waka Readme

on:
  schedule:
    # Runs at 12am IST
    - cron: '30 18 * * *'
  workflow_dispatch:
jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: anmol098/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ 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 }}
          GH_TOKEN: ${{ 3024fdb9-5409-410e-b0ef-cd82d8cc04c6 }}
<!--END_SECTION:waka-->
