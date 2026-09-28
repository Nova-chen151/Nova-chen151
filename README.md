<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0%3A7AA2FF%2C55%3A8C8FF5%2C100%3A78C8E8&height=220&section=header&text=NOVA&fontSize=64&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Generative%20Simulation%20%C2%B7%20Autonomous%20Driving%20%C2%B7%203D%20Reconstruction&descAlignY=58&descSize=18" width="100%" alt="NOVA banner" />
</p>

<h1 align="center">From Real-world Videos to Reliable Policy Tests</h1>

<p align="center">
  <a href="https://github.com/Nova-chen151"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="https://ojs.aaai.org/index.php/AAAI/article/view/36970"><img src="https://img.shields.io/badge/CDPT-AAAI%202026-3B82F6?style=for-the-badge" /></a>
  <a href="https://www.onsite.com.cn/"><img src="https://img.shields.io/badge/OnSite-616161?style=for-the-badge" /></a>
  <a href="https://nova-chen151.github.io/Onsite3DSG-Benchmark.github.io/"><img src="https://img.shields.io/badge/3DSG%20Benchmark-6366F1?style=for-the-badge" /></a>
  <a href="https://github.com/Nova-chen151?tab=followers"><img src="https://img.shields.io/github/followers/Nova-chen151?label=Followers&style=for-the-badge&color=6366F1" /></a>
</p>

<p align="center">
  <b>让生成场景真正成为可信的自动驾驶测试。</b><br/>
  <sub>From generated scenes to trustworthy policy tests.</sub>
</p>

<p align="center">
  <a href="#-about-me">About</a> ·
  <a href="#-onsite-timeline">OnSite</a> ·
  <a href="#-selected-publications">Publications</a> ·
  <a href="#-contribution-snake">Snake</a>
</p>

---

## 👋 About Me

你好，我是 **Nova**。我的研究关注 **自动驾驶场景生成、三维场景重建与闭环仿真测试**，希望让真实驾驶数据与生成模型共同服务于驾驶策略的训练、测试和改进。

- 🚗 **生成式仿真与策略测试**：研究生成场景的交通合理性、策略响应，以及场景是否具有可信的测试价值。
- 🎥 **从视频到可交互场景**：探索行车视频重建、长时序场景表示与闭环测试之间的连接。
- 🧠 **多智能体行为建模**：关注交通行为生成、轨迹重建，以及不完整观测下的运动建模。

---

## 🛣️ OnSite Timeline

### OnSite 3.0 · Rule-driven Scenario Generation

**[Onsite_rule_driven_model](https://github.com/Nova-chen151/Onsite_rule_driven_model)**

面向 OnSite 智能场景生成赛道的规则驱动 baseline，围绕背景交通参与者构建跟驰、换道、合流、分流与冲突交互等典型微观交通行为。

<p>
  <a href="https://github.com/Nova-chen151/Onsite_rule_driven_model"><img src="https://img.shields.io/badge/Code-Onsite__rule__driven__model-181717?style=flat-square&logo=github&logoColor=white" /></a>
</p>

### OnSite · Scenario Evaluation & Replay Testing

**[Onsite_Ego_Testing](https://github.com/Nova-chen151/Onsite_Ego_Testing)**

围绕生成场景构建离线回放与评测流程，将场景接入多个规划器，完成回放测试、指标计算、评分汇总与 GIF 可视化。

<p>
  <a href="https://github.com/Nova-chen151/Onsite_Ego_Testing"><img src="https://img.shields.io/badge/Code-Onsite__Ego__Testing-181717?style=flat-square&logo=github&logoColor=white" /></a>
</p>

### OnSite 4.0 · Unified Train-Test Scenario Generation

**[Onsite_Data-driven_Baseline](https://github.com/Nova-chen151/Onsite_Data-driven_Baseline)** · **[Onsite_UT2SG_Testing](https://github.com/Nova-chen151/Onsite_UT2SG_Testing)**

从数据驱动背景车生成进一步扩展到 **BV–AV 联合评测**：一侧生成背景交通场景，另一侧评测自动驾驶策略在场景中的闭环表现，推动“场景生成—策略测试”形成完整链路。

<p>
  <a href="https://github.com/Nova-chen151/Onsite_Data-driven_Baseline"><img src="https://img.shields.io/badge/Code-Data--driven%20Baseline-181717?style=flat-square&logo=github&logoColor=white" /></a>
  <a href="https://github.com/Nova-chen151/Onsite_UT2SG_Testing"><img src="https://img.shields.io/badge/Code-UT2SG%20Testing-181717?style=flat-square&logo=github&logoColor=white" /></a>
</p>

### OnSite 3D Scenario Generation Benchmark

**[OnSite 3DSG Benchmark](https://nova-chen151.github.io/Onsite3DSG-Benchmark.github.io/)**

当前正在推进的三维场景生成 Benchmark，关注生成场景是否不仅“看起来真实”，更能成为 **trustworthy policy tests**。

<p>
  <a href="https://nova-chen151.github.io/Onsite3DSG-Benchmark.github.io/"><img src="https://img.shields.io/badge/Project-Page-6366F1?style=flat-square" /></a>
  <a href="https://github.com/Nova-chen151/Onsite3DSG-Benchmark.github.io"><img src="https://img.shields.io/badge/Code-Repository-181717?style=flat-square&logo=github&logoColor=white" /></a>
</p>

---

## 📝 Selected Publications

### CDPT · AAAI 2026

**[Transferring Causal Driving Patterns for Generalizable Traffic Simulation with Diffusion-Based Distillation](https://ojs.aaai.org/index.php/AAAI/article/view/36970)**  
Yuhang Chen, Jie Sun, Jialin Fan, Jian Sun

面向跨域交通仿真的因果驾驶模式迁移与扩散蒸馏。

<p>
  <a href="https://ojs.aaai.org/index.php/AAAI/article/view/36970"><img src="https://img.shields.io/badge/Paper-AAAI%202026-3B82F6?style=flat-square" /></a>
  <a href="https://github.com/Nova-chen151/SIM-CDPT"><img src="https://img.shields.io/badge/Code-SIM--CDPT-181717?style=flat-square&logo=github&logoColor=white" /></a>
  <a href="https://nova-chen151.github.io/simCDPT.github.io/"><img src="https://img.shields.io/badge/Project-Page-6366F1?style=flat-square" /></a>
</p>

---

## 🐍 Contribution Snake

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
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0%3A7AA2FF%2C55%3A8C8FF5%2C100%3A78C8E8&height=110&section=footer" width="100%" alt="footer" />
</p>
