<!-- ==================== Header ==================== -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0%3A2563EB%2C55%3A6366F1%2C100%3A38BDF8&height=210&section=header&text=NOVA&fontSize=62&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Autonomous%20Driving%20%C2%B7%20Scenario%20Generation%20%C2%B7%20Simulation%20%26%20Testing&descAlignY=57&descSize=17" width="100%" alt="NOVA" />
</p>

<p align="center">
  <a href="https://github.com/Nova-chen151">
    <img src="https://readme-typing-svg.demolab.com/?font=Fira%20Code&weight=600&size=22&duration=2800&pause=1800&color=5B6FE8&center=true&vCenter=true&width=980&height=55&lines=Three+Editions+of+OnSite+%C2%B7+One+Continuous+Journey;Scenario+Generation+%E2%86%92+Simulation+%E2%86%92+Policy+Testing;Generative+Driving+%C2%B7+Closed-loop+Evaluation" width="100%" alt="OnSite journey" />
  </a>
</p>

<p align="center">
  <a href="https://www.onsite.com.cn/">
    <img src="https://img.shields.io/badge/OnSite-Autonomous_Driving_Challenge-2563EB?style=for-the-badge" alt="OnSite" />
  </a>
  <a href="https://nova-chen151.github.io/Onsite3DSG-Benchmark.github.io/">
    <img src="https://img.shields.io/badge/OnSite_3DSG-Benchmark-6366F1?style=for-the-badge" alt="OnSite 3DSG Benchmark" />
  </a>
  <a href="https://github.com/Nova-chen151?tab=repositories">
    <img src="https://img.shields.io/badge/GitHub-Repositories-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repositories" />
  </a>
</p>

<p align="center">
  <b>让生成场景真正服务于自动驾驶测试。</b><br/>
  <sub>Building driving scenarios that are not only realistic, but useful for testing.</sub>
</p>

---

## 👋 About Me

你好，我是 **Nova**。我的研究主要关注 **自动驾驶场景生成、交通仿真、三维场景重建与闭环策略测试**。

过去三届 **OnSite 自动驾驶算法挑战赛** 中，我持续参与场景生成与测试相关技术工作。围绕赛事需求，我的工作逐步从 **规则驱动交通仿真**，扩展到 **生成场景评测与多策略测试**，再进一步探索 **数据驱动生成、训测一体以及 3D 生成场景 Benchmark**。

<p align="center">
  <img src="https://img.shields.io/badge/-Autonomous%20Driving-2563EB?style=flat-square"/>
  <img src="https://img.shields.io/badge/-Scenario%20Generation-4F46E5?style=flat-square"/>
  <img src="https://img.shields.io/badge/-Traffic%20Simulation-6366F1?style=flat-square"/>
  <img src="https://img.shields.io/badge/-Closed--loop%20Testing-0284C7?style=flat-square"/>
  <img src="https://img.shields.io/badge/-3D%20Scene%20Generation-0891B2?style=flat-square"/>
</p>

---

## 🏁 Three Editions of OnSite

<p align="center">
  <b>Scenario Generation → Simulation → Policy Testing → Evaluation → Feedback</b>
</p>

<p align="center">
  <sub>从“如何生成场景”，逐步走向“如何判断生成场景是否真正具有测试价值”。</sub>
</p>

<table width="100%">
  <tr>
    <td align="center" width="23%">
      <b>① Rule-based Simulation</b><br/><br/>
      <sub>规则驱动交通行为建模</sub><br/>
      <sub>跟驰 · 换道 · 合流 · 分流 · 冲突</sub><br/><br/>
      <a href="https://github.com/Nova-chen151/Onsite_rule_driven_model"><b>Repository ↗</b></a>
    </td>
    <td align="center" width="3%">➜</td>
    <td align="center" width="23%">
      <b>② Scenario Evaluation</b><br/><br/>
      <sub>生成场景回放与多规划器测试</sub><br/>
      <sub>Safety · Comfort · Realism</sub><br/><br/>
      <a href="https://github.com/Nova-chen151/Onsite_Ego_Testing"><b>Repository ↗</b></a>
    </td>
    <td align="center" width="3%">➜</td>
    <td align="center" width="23%">
      <b>③ Unified Train-Test</b><br/><br/>
      <sub>数据驱动背景车生成 + BV–AV 联合评测</sub><br/>
      <sub>Generation · Policy · Scoring</sub><br/><br/>
      <a href="https://github.com/Nova-chen151/Onsite_Data-driven_Baseline"><b>Baseline ↗</b></a> ·
      <a href="https://github.com/Nova-chen151/Onsite_UT2SG_Testing"><b>Testing ↗</b></a>
    </td>
    <td align="center" width="3%">➜</td>
    <td align="center" width="22%">
      <b>④ 3D Generative Benchmark</b><br/><br/>
      <sub>三维生成场景与策略测试基准</sub><br/>
      <sub>Quality · Fidelity · Response · QTES</sub><br/><br/>
      <a href="https://nova-chen151.github.io/Onsite3DSG-Benchmark.github.io/"><b>Project Page ↗</b></a>
    </td>
  </tr>
</table>

> **What I care about:** generated scenarios should not only look realistic. They should provide **credible and useful tests for autonomous-driving policies**.

---

## 🚀 Featured OnSite Projects

### 🧩 Rule-driven Scenario Generation
**[Onsite_rule_driven_model](https://github.com/Nova-chen151/Onsite_rule_driven_model)**

第三届 OnSite 智能场景生成赛道相关样例模型。以规则驱动方式构建背景交通行为，包含 IDM 跟驰、换道、合流、分流、冲突避让等典型微观交通行为。

### 🧪 Scenario & Policy Evaluation
**[Onsite_Ego_Testing](https://github.com/Nova-chen151/Onsite_Ego_Testing)**

生成场景离线回放与评测工具，将生成场景接入多个规划器，完成场景回放、指标计算、汇总评分与 GIF 可视化。

### 🤖 Data-driven Scenario Generation
**[Onsite_Data-driven_Baseline](https://github.com/Nova-chen151/Onsite_Data-driven_Baseline)**

面向 OnSite 训测一体场景生成任务的数据驱动 baseline，根据历史交通状态与 OpenDRIVE 路网预测背景车辆行为，并生成 OpenSCENARIO 兼容测试场景。

### 📊 Unified Train-Test Evaluation
**[Onsite_UT2SG_Testing](https://github.com/Nova-chen151/Onsite_UT2SG_Testing)**

连接 **BV 场景生成质量** 与 **AV 自车闭环表现** 的统一评测流程，支持多算法测试并输出场景级和汇总评分结果。

### 🌐 OnSite 3D Scenario Generation Benchmark
**[Project Page](https://nova-chen151.github.io/Onsite3DSG-Benchmark.github.io/)** · **[Repository](https://github.com/Nova-chen151/Onsite3DSG-Benchmark.github.io)**

当前正在推进的三维场景生成 Benchmark。核心问题是：

> **Can generated driving scenarios become trustworthy policy tests?**

评测从 **Observation Quality → Scenario Fidelity → Policy Response → Quality-Aware Testing Effectiveness** 逐层展开，使生成场景的评价不再停留在“看起来像不像真实世界”。

---

## 🔬 Research Interests

- **Generative Driving Simulation** — 可控、可扩展的自动驾驶测试场景生成
- **Closed-loop Simulation & Policy Testing** — 将生成环境真正接入驾驶策略测试
- **3D Scene Generation & Reconstruction** — 从真实观测构建可交互三维驾驶环境
- **Multi-agent Trajectory Modeling** — 交通行为生成、轨迹预测与轨迹重建
- **Real2Sim / Sim2Real** — 连接真实驾驶数据、重建环境与仿真测试

---

## 📌 Selected Projects

<p align="center">
  <a href="https://github.com/Nova-chen151/Onsite3DSG-Benchmark.github.io">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Nova-chen151&repo=Onsite3DSG-Benchmark.github.io&theme=transparent" />
  </a>
  <a href="https://github.com/Nova-chen151/Onsite_Data-driven_Baseline">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Nova-chen151&repo=Onsite_Data-driven_Baseline&theme=transparent" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/Nova-chen151/Onsite_UT2SG_Testing">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Nova-chen151&repo=Onsite_UT2SG_Testing&theme=transparent" />
  </a>
  <a href="https://github.com/Nova-chen151/TrajBridge">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Nova-chen151&repo=TrajBridge&theme=transparent" />
  </a>
</p>

---

## 🛠️ Tools

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenSCENARIO-2563EB?style=flat-square"/>
  <img src="https://img.shields.io/badge/OpenDRIVE-4F46E5?style=flat-square"/>
</p>

---

## 📈 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Nova-chen151&show_icons=true&hide_border=true&include_all_commits=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Nova-chen151&layout=compact&hide_border=true" />
</p>

### 🐍 Contribution Snake

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Nova-chen151/Nova-chen151/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Nova-chen151/Nova-chen151/output/github-contribution-grid-snake.svg">
    <img alt="GitHub contribution grid snake animation" src="https://raw.githubusercontent.com/Nova-chen151/Nova-chen151/output/github-contribution-grid-snake.svg">
  </picture>
</p>

---

<p align="center">
  <b>AI for driving scenarios, driving scenarios for AI.</b><br/>
  <sub>AI 服务 AI · From scenario generation to trustworthy policy testing.</sub>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0%3A2563EB%2C55%3A6366F1%2C100%3A38BDF8&height=100&section=footer" width="100%" alt="footer" />
</p>
