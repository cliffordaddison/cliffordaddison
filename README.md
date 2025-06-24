<!-- 🎯 Dynamic Typing Animation -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=28&pause=2000&color=06B6D4&center=true&vCenter=true&width=650&lines=Hi,+I'm+Clifford+Addison!;AI+%7C+Data+Science+%7C+Ops+%7C+Always+Learning" alt="Typing SVG" />
</p>

---

### 👋 About Me

Hi, I'm **Clifford Addison** — an **AI & Data Science student** at Loyalist College, Toronto, with a BSc in Actuarial Science and a rich 8+ year background managing logistics and operations across Africa’s mining, maritime, and infrastructure industries. I design insightful ML models and interactive apps.

---

### 🎓 Journey & 💼 Experience

| Level | Details |
|------|---------|
| 🎓 Education | AI & DS (Loyalist College, 2024–25) • Actuarial Science (KNUST, Ghana) |
| 💼 Experience | Ops Manager → GM—Technical Security & Logistics |
| 🌐 Pivoting into | AI, ML, NLP, Deep Learning, Model Interpretability, Data Visualization |

---

### 🌐 Socials

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/cliffordaddison) [![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github)](https://github.com/cliffordaddison) [![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail)](mailto:clifford.siisi.addison@gmail.com)

---

### 💻 Tech Toolkit

- **Languages:** Python • SQL • JavaScript  
- **ML & Data:** pandas • NumPy • Scikit-Learn • TensorFlow • SHAP • LIME  
- **Deployment & DevOps:** Streamlit • Docker • Git • Linux  
- **Visualization:** Matplotlib • Seaborn • Tableau • Power BI

---

### 🚀 Highlighted Projects

- **Weather Forecasting ML** *(Regression, SHAP, Docker, Streamlit)*  
- **Fake News Detector** *(NLP, LSTM/XGBoost, Interpretability)*  
- **Loan Eligibility Predictor** *(Streamlit UI, RF, Cross‑Validation)*  
- **Insurance Cost Regressor** *(BMI, Age, Smoke; Streamlit App)*

---

### 📊 GitHub Stats & Activities

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=cliffordaddison&show_icons=true&theme=default" alt="GitHub Stats" />
</p>
<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=cliffordaddison&theme=default" alt="GitHub Streak" />
</p>
<p align="center">
  <img src="https://github-readme-activity-graph.cyclic.app/graph?username=cliffordaddison&theme=light" alt="Activity Graph" />
</p>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=cliffordaddison&layout=compact" alt="Top Languages" />

---

### 🐍 Contribution Snake

![Contribution Snake](./github-contribution-grid-snake.svg)

*Powered by GitHub Action: `Platane/snk`*

---

### 🧩 GitHub Action Setup

To auto-update the snake animation:

```yaml
name: Generate Snake
on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:
jobs:
  snake:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          svg_out_path: github-contribution-grid-snake.svg
