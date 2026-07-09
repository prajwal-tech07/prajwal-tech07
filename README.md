<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Prajwal%20Hawaldar&fontSize=50&fontColor=fff&animation=twinkling&fontAlignY=35&desc=GSoC%202026%20Contributor%20%40%20MLLAM%20%7C%20ML%20Engineer%20%7C%20Open%20Source&descSize=18&descAlignY=55" width="100%" />
</div>

<div align="center">
  <a href="https://summerofcode.withgoogle.com/"><img src="https://img.shields.io/badge/GSoC%202026-Contributor-fbbc05?style=for-the-badge&logo=google&logoColor=white" /></a>
  <a href="mailto:prajwalhawaldar2@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://linkedin.com/in/prajwal-hawaldar-190197279"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://twitter.com/pr51283"><img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" /></a>
  <a href="https://instagram.com/its_prajwal_100412"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" /></a>
  <a href="https://leetcode.com/u/prazziii/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" /></a>
</div>

<br/>

## 🧑‍💻 About Me

<table>
<tr>
<td width="62%" valign="top">

- 🌦️ **Google Summer of Code 2026 contributor @ [MLLAM](https://github.com/mllam)** — building flexible graph construction for AI weather models
- 🔭 Working at the intersection of **Graph Neural Networks, PyTorch & scientific computing**
- 🌱 Learning **Advanced Deep Learning, LLMs & Transformers**
- 🤝 Open to collaborating on **ML, Data Science & Open Source projects**
- 💬 Ask me about **GNNs, PyTorch, ML-based weather prediction & Data Science**
- ⚡ Fun fact: *"90% of Data Science is cleaning data, 10% is complaining about it"* 😄

</td>
<td width="38%" align="center" valign="middle">

<img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="100%" alt="coding gif" />

</td>
</tr>
</table>

---

## 🌦️ Google Summer of Code 2026 — MLLAM

<div align="center">
  <a href="https://summerofcode.withgoogle.com/">
    <img src="https://img.shields.io/badge/Google%20Summer%20of%20Code-2026-fbbc05?style=for-the-badge&logo=google&logoColor=white" />
  </a>
  <a href="https://github.com/mllam">
    <img src="https://img.shields.io/badge/Organization-MLLAM-2b6cb0?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <img src="https://img.shields.io/badge/Project-350%20hours-34a853?style=for-the-badge" />
</div>

<br/>

> **Project: Flexible Graph Construction for Neural Weather Models**
>
> [MLLAM](https://github.com/mllam) (Machine Learning for Limited Area Models) is an open-source collaboration of meteorological institutes and researchers building **data-driven regional weather forecasting** — GraphCast-style GNN models that run the encode → process → decode cycle over mesh graphs.
>
> My project makes mesh-graph construction **topology-agnostic** across the MLLAM stack, so researchers can swap rectangular, triangular (Delaunay), or fully custom meshes into the same forecasting pipeline — instead of being locked into one hardcoded grid.

**🧑‍🏫 Mentors:** [Leif Denby](https://github.com/leifdenby) · [Hauke Schulz](https://github.com/observingClouds) · [Joel Oskarsson](https://github.com/joeloskarsson)

### 📦 Repositories I work on

<div align="center">

<a href="https://github.com/mllam/weather-model-graphs">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=mllam&repo=weather-model-graphs&theme=tokyonight&hide_border=true&description_lines_count=2" />
</a>
<a href="https://github.com/mllam/neural-lam">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=mllam&repo=neural-lam&theme=tokyonight&hide_border=true&description_lines_count=2" />
</a>

</div>

### 🚀 Contributions

| Contribution | Repo | Status |
|---|---|---|
| [**#81**](https://github.com/mllam/weather-model-graphs/pull/81) — Two-step `mesh_layout` architecture separating mesh **coordinate creation** from **connectivity** — the foundation for all alternative mesh topologies | `weather-model-graphs` | ✅ **Merged** |
| [**#92**](https://github.com/mllam/weather-model-graphs/pull/92) — **Triangular (Delaunay) multi-range meshes** as the first alternative topology, built on the new layout architecture | `weather-model-graphs` | 🔄 In review |
| [**#123**](https://github.com/mllam/weather-model-graphs/pull/123) — `to_torch_tensors_on_disk`: standardized **on-disk graph serialization** so any WMG graph loads directly into neural-lam | `weather-model-graphs` | 🔄 In review |
| [**#596**](https://github.com/mllam/neural-lam/pull/596) — `create_graph_with_wmg` **bridge CLI**, replacing 600+ lines of duplicated graph-construction code in neural-lam with the shared WMG library | `neural-lam` | 🔄 In review |
| [**#79**](https://github.com/mllam/weather-model-graphs/issues/79) — **Prebuilt / bring-your-own mesh layouts**: design for injecting externally-generated meshes (e.g. from existing NWP model grids) | `weather-model-graphs` | 🧩 Design agreed with maintainers |
| [**#144**](https://github.com/mllam/weather-model-graphs/issues/144) — **CI benchmark regression detection** for graph-construction performance | `weather-model-graphs` | 🧩 Proposal accepted |

### 🗺️ Roadmap

```
Layer 1  ✅  Mesh layout architecture — rectangular + triangular (Delaunay) topologies
Layer 2  🔄  Bridge: one shared graph pipeline + on-disk format between WMG and neural-lam
Layer 3  🔜  Migrate neural-lam's internal graph representation to PyG HeteroData
Layer 4+ 🌟  Graph quality metrics, density-adaptive meshes, spherical coordinates
```

*Why it matters: ML-based weather forecasting is becoming operational at national weather services. Flexible mesh construction lets scientists match the graph to the physics — finer resolution where the weather is complex — rather than the other way around.*

---

## 🏆 Achievements

<div align="center">

| | Achievement | Year |
|:---:|:---|:---:|
| 🌦️ | **Google Summer of Code Contributor** — [MLLAM](https://github.com/mllam) · Flexible Graph Construction for neural weather models (350h project) | 2026 |
| 📚 | **Amazon ML Summer School** — Shortlisted (Amazon India) | 2026 |
| 🦈 | **GitHub Pull Shark & Pair Extraordinaire** — earned through merged PRs and collaborative work | — |
| 🧩 | **Competitive programming** on [LeetCode](https://leetcode.com/u/prazziii/) | — |

</div>

---

## 🛠️ Tech Stack

<div align="center">

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

### Machine Learning & AI
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![PyTorch Geometric](https://img.shields.io/badge/PyTorch%20Geometric-3C2179?style=for-the-badge&logo=pyg&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

### Data Science & Scientific Computing
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)
![NetworkX](https://img.shields.io/badge/NetworkX-2C7FB8?style=for-the-badge&logo=python&logoColor=white)
![Xarray](https://img.shields.io/badge/Xarray-0F4C81?style=for-the-badge&logo=python&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=plotly&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)

### Tools & Platforms
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Weights & Biases](https://img.shields.io/badge/W%26B-FFBE00?style=for-the-badge&logo=weightsandbiases&logoColor=black)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)

</div>

---

## 🌍 Open Source

<div align="center">

I contribute to open-source **Machine Learning & Scientific Computing** projects — currently as a
**Google Summer of Code 2026 contributor** with [MLLAM](https://github.com/mllam), working on
graph construction for neural weather prediction models used in real forecasting research.

![Open Source](https://img.shields.io/badge/Open%20Source-❤️-red?style=for-the-badge)
![GSoC 2026](https://img.shields.io/badge/GSoC-2026-fbbc05?style=for-the-badge&logo=google&logoColor=white)
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen?style=for-the-badge)

*I believe in building in the open and giving back to the community.*

</div>

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=prajwal-tech07&theme=tokyonight&no-frame=true&no-bg=true&row=1&column=7&margin-w=8" />
</div>

<br/>

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=prajwal-tech07&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" />
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=prajwal-tech07&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />
</div>

<br/>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=prajwal-tech07&theme=tokyonight&hide_border=true" />
</div>

---

## 📈 Contribution Graph

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=prajwal-tech07&theme=tokyo-night&hide_border=true&area=true" />
</div>

---

## 🐍 Contribution Snake

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/prajwal-tech07/prajwal-tech07/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/prajwal-tech07/prajwal-tech07/output/github-snake.svg" />
    <img alt="github contribution snake animation" src="https://raw.githubusercontent.com/prajwal-tech07/prajwal-tech07/output/github-snake.svg" />
  </picture>
</div>

---

## 📫 Let's Connect

<div align="center">

💡 *I'm always open to interesting conversations, collaborations, and opportunities!*

<a href="mailto:prajwalhawaldar2@gmail.com"><img src="https://img.shields.io/badge/Drop%20me%20an-Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://linkedin.com/in/prajwal-hawaldar-190197279"><img src="https://img.shields.io/badge/Connect%20on-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>

</div>

---

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=prajwal-tech07&style=for-the-badge&color=6C63FF&label=PROFILE+VIEWS" />
</div>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" width="100%" />
</div>
