### Hi there 👋


<!-- **neshvig10/neshvig10** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile. -->

<!-- Here are some ideas to get you started: -->

- 🔭 I’m currently working on some cool projects
- 🌱 I’m currently learning and Web3
- 👯 I’m looking to collaborate on interesting projects which involves MERN stack
- 🤔 I’m looking for help with Open Source Contributions
- 💬 Ask me about Front End Development
- 📫 How to reach me: s.vigneshwaran.cse21@iitbhu.ac.in
- 😄 Pronouns: he/him
<!-- - ⚡ Fun fact: ... -->


![](https://raw.githubusercontent.com/neshvig10/github-stats/master/generated/overview.svg#gh-dark-mode-only)
![](https://raw.githubusercontent.com/neshvig10/github-stats/master/generated/overview.svg#gh-light-mode-only)
[![GitHub Streak](https://streak-stats.demolab.com/?user=neshvig10)](https://git.io/streak-stats)

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
      - uses: neshvig10/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
          GH_TOKEN: ${{ secrets.GH_TOKEN }}
