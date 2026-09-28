# Drew

**ML / AI engineer.** I build models that make predictions under real uncertainty — and I care more about whether they beat an honest baseline than whether the architecture is fashionable.

Currently working on time-series forecasting for atmospheric data: satellite and reanalysis inputs, neural sequence models, and the unglamorous evaluation discipline that keeps results from being an illusion.

---

## 🔭 Featured work

### [Paris AQI Forecasting](https://github.com/DrewVII/Paris-AQI-Forecasting)
Hourly air-quality forecasting from NASA GEOS-CF reanalysis. A GRU predicts EPA AQI 24 hours ahead with median and 90th-percentile outputs.

- **~30% lower MAE than persistence**, peaking at 32% skill at 12–18h lead time
- Residual targets, so the baseline is the model's floor rather than its competitor
- Quantile (pinball) loss to stop the forecast hedging low during pollution episodes
- Leakage-checked evaluation: chronological splits, train-only scalers, verified window alignment

`PyTorch` · `Google Earth Engine` · `pandas` · `NumPy`

---

## 🧰 Stack

**ML & data**

<p align="left">
  <a href="https://pytorch.org/" target="_blank"><img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?logo=pytorch&logoColor=white"></a>
  <a href="https://numpy.org" target="_blank"><img alt="NumPy" src="https://img.shields.io/badge/NumPy-%23013243.svg?logo=numpy&logoColor=white"></a>
  <a href="https://pandas.pydata.org" target="_blank"><img alt="pandas" src="https://img.shields.io/badge/pandas-%23150458.svg?logo=pandas&logoColor=white"></a>
  <a href="https://scikit-learn.org" target="_blank"><img alt="scikit-learn" src="https://img.shields.io/badge/scikit--learn-%23F7931E.svg?logo=scikit-learn&logoColor=white"></a>
  <a href="https://lightning.ai" target="_blank"><img alt="Lightning" src="https://img.shields.io/badge/Lightning-%23792EE5.svg?logo=lightning&logoColor=white"></a>
  <a href="https://opencv.org" target="_blank"><img alt="OpenCV" src="https://img.shields.io/badge/OpenCV-%235C3EE8.svg?logo=opencv&logoColor=white"></a>
  <a href="https://earthengine.google.com/" target="_blank"><img alt="Earth Engine" src="https://img.shields.io/badge/Earth%20Engine-%234285F4.svg?logo=googleearth&logoColor=white"></a>
</p>

**Languages**

<p align="left">
  <a href="https://www.python.org" target="_blank"><img alt="Python" src="https://img.shields.io/badge/Python-%2314354C.svg?logo=python&logoColor=white"></a>
  <a href="https://www.cprogramming.com/" target="_blank"><img alt="C" src="https://img.shields.io/badge/C-%232370ED.svg?logo=c&logoColor=white"></a>
  <a href="https://www.w3schools.com/cpp/" target="_blank"><img alt="C++" src="https://img.shields.io/badge/C++-%2300599C.svg?logo=c%2B%2B&logoColor=white"></a>
  <a href="https://www.java.com" target="_blank"><img alt="Java" src="https://img.shields.io/badge/Java-%23ED8B00.svg?logo=java&logoColor=white"></a>
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank"><img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?logo=javascript&logoColor=black"></a>
  <a href="https://www.gnu.org/software/bash/" target="_blank"><img alt="Bash" src="https://img.shields.io/badge/Bash-%23121011.svg?logo=gnu-bash&logoColor=white"></a>
</p>

**Infrastructure**

<p align="left">
  <a href="https://www.docker.com/" target="_blank"><img alt="Docker" src="https://img.shields.io/badge/Docker-%230db7ed.svg?logo=docker&logoColor=white"></a>
  <a href="https://aws.amazon.com/" target="_blank"><img alt="AWS" src="https://img.shields.io/badge/AWS-%23FF9900.svg?logo=amazon-aws&logoColor=white"></a>
  <a href="https://www.postgresql.org/" target="_blank"><img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-%23316192.svg?logo=postgresql&logoColor=white"></a>
  <a href="https://www.mongodb.com/" target="_blank"><img alt="MongoDB" src="https://img.shields.io/badge/MongoDB-%234ea94b.svg?logo=mongodb&logoColor=white"></a>
  <a href="https://git-scm.com/" target="_blank"><img alt="Git" src="https://img.shields.io/badge/Git-%23F05033.svg?logo=git&logoColor=white"></a>
  <a href="https://www.linux.org/" target="_blank"><img alt="Linux" src="https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black"></a>
</p>

<details>
<summary>Also work with</summary>

Django · Flask · Express.js · Socket.io · Selenium · MySQL · SQLite · Firebase · Nginx · HTML/CSS · Tailwind · Flutter · Arduino

</details>

---

## 📊 What I'm working on

- Validating the AQI model against ground-station measurements (OpenAQ / EEA) rather than reanalysis alone
- Column-to-surface mapping from satellite retrievals — TROPOMI for Europe, TEMPO for North America
- Reading more about probabilistic forecasting and proper scoring rules

---

## 📫 Reach me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/amakuisa/)

---

<sub>⭐️ From [Drew](https://github.com/DrewVII)</sub>
