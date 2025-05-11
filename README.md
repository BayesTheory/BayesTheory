# Rian Ferreira 🧠📊
**AI/ML Developer** • **Statistics & Civil Engineering Student** • **Computer Science Technician**

🎯 Precision, performance, and a dash of aesthetic  | 🧪 Data & Automation enthusiast  


---

### 🔧 Developer Profile Snapshot

- 🔍 **Focus:** AI/ML • Data Automation • Bayesian Modeling
- 📚 **Current Stack:** Python, R, C, TensorFlow, Docker, SQL
- 🧠 **Learning:** MLOps • Probabilistic Programming • Cloud Pipelines
- 🌐 **Contributions:** GitHub, LAMCE/UFRJ, Open Data Projects, UFRJ Community

---
name: GitHub-Profile-3D-Contrib

on:
  schedule: # 03:00 JST == 18:00 UTC
    - cron: "0 18 * * *"
  workflow_dispatch:

permissions:
  contents: write

jobs:
  build:
    runs-on: ubuntu-latest
    name: generate-github-profile-3d-contrib
    steps:
      - uses: actions/checkout@v4
      - uses: yoshi389111/github-profile-3d-contrib@latest
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
          USERNAME: ${{ github.repository_owner }}
      - name: Commit & Push
        run: |
          git config user.name github-actions
          git config user.email github-actions@github.com
          git add -A .
          if git commit -m "generated"; then
            git push
          fi
  
### 🌌 Skill Set Highlights

![Python](https://img.shields.io/badge/Python-333?style=for-the-badge&logo=python&logoColor=FFD43B)
![TensorFlow](https://img.shields.io/badge/TensorFlow-333?style=for-the-badge&logo=tensorflow&logoColor=FF6F00)
![R](https://img.shields.io/badge/R-333?style=for-the-badge&logo=r&logoColor=75AADB)
![Apache Spark](https://img.shields.io/badge/Spark-333?style=for-the-badge&logo=apachespark&logoColor=E25A1C)
![Docker](https://img.shields.io/badge/Docker-333?style=for-the-badge&logo=docker&logoColor=0db7ed)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-333?style=for-the-badge&logo=postgresql&logoColor=336791)

---
