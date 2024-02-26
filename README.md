# About me 
----------
- 😎 My name is Luccas,

##

## :hammer_and_wrench: Languages and Tools :

<div>
    <img src="https://github.com/devicons/devicon/blob/master/icons/csharp/csharp-original.svg" title="C#" **alt="C#" width="40" height="40"/>
    <img src="https://github.com/devicons/devicon/blob/master/icons/java/java-original.svg" title="Java" alt="Java" width="40" height="40"/>&nbsp;
    <img src="https://github.com/devicons/devicon/blob/master/icons/vscode/vscode-original.svg" title="VSCode" **alt="VSCode" width="40" height="40"/>
    <img src="https://github.com/devicons/devicon/blob/master/icons/visualstudio/visualstudio-plain.svg" title="VisualStudio" **alt="VisualStudio" width="40" height="40"/>
    <img src="https://github.com/devicons/devicon/blob/master/icons/sqldeveloper/sqldeveloper-original.svg" title="sqldeveloper" **alt="sqldeveloper" width="40" height="40"/>
</div>

## What I'm coding?

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=LuccasSilvaDev&theme=dark&PAT_1)](https://github.com/LuccasSilvaDev/github-readme-stats&PAT_1)

## :fire: My Stats :

[![GitHub Streak](http://github-readme-streak-stats.herokuapp.com?user=LuccasSilvaDev&theme=dark&background=000000)](https://git.io/streak-stats)
  
 ## Where you can find me? 📫
 
<div> 
  <a href = "mailto:luccassilvadev@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=Gmail&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/LuccasSilvaDev" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
  <a href = "http://api.whatsapp.com/send?phone=5515991124179"><img src="https://img.shields.io/badge/-whatsapp-%23333?style=for-the-badge&logo=whatsapp&logoColor=white" target="_blank"></a>
</div>

<!--START_SECTION:waka-->
name: Waka Readme

on:
  schedule:
    # Runs at 12am IST
    - cron: '30 18 * * *'

jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: anmol098/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
          GH_TOKEN: ${{ secrets.GH_TOKEN }}
<!--END_SECTION:waka-->
