<!-- ==================== Header ==================== -->

<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0%3A7AA2FF%2C55%3A8C8FF5%2C100%3A78C8E8&height=220&section=header&text=NOVA&fontSize=64&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Generative%20Simulation%20%C2%B7%20Autonomous%20Driving%20%C2%B7%203D%20Reconstruction&descAlignY=58&descSize=18"
    width="100%"
    alt="NOVA"
  />
</p>

<!-- ==================== Dynamic Typing ==================== -->

<p align="center">
  <a href="https://github.com/Nova-chen151">
    <img
      src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=700&size=28&duration=2800&pause=1200&color=6C7BFF&center=true&vCenter=true&width=950&height=60&lines=From+Real-world+Videos+to+Reliable+Policy+Tests;Generative+Driving+%C2%B7+Closed-loop+Simulation;Scenario+Generation+%C2%B7+3D+Reconstruction+%C2%B7+Policy+Testing"
      alt="Typing SVG"
    />
  </a>
</p>

<!-- ==================== Badges ==================== -->

<p align="center">
  <a href="https://github.com/Nova-chen151">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>

  <a href="https://ojs.aaai.org/index.php/AAAI/article/view/36970">
    <img src="https://img.shields.io/badge/CDPT-AAAI%202026-3B82F6?style=for-the-badge" />
  </a>

  <a href="https://www.onsite.com.cn/">
    <img src="https://img.shields.io/badge/OnSite-Autonomous%20Driving-555555?style=for-the-badge" />
  </a>

  <a href="https://nova-chen151.github.io/Onsite3DSG-Benchmark.github.io/">
    <img src="https://img.shields.io/badge/3DSG-Benchmark-6366F1?style=for-the-badge" />
  </a>

  <a href="https://github.com/Nova-chen151?tab=followers">
    <img src="https://img.shields.io/github/followers/Nova-chen151?label=Followers&style=for-the-badge&color=6366F1&logo=github&logoColor=white" />
  </a>
</p>

<p align="center">
  <b>让生成场景真正成为可信的自动驾驶测试。</b><br/>
  <sub>From generated scenes to trustworthy policy tests.</sub>
</p>

<p align="center">
  <a href="#-about-me">About</a> ·
  <a href="#️-onsite-timeline">OnSite</a> ·
  <a href="#-selected-publications">Publications</a> ·
  <a href="#-contribution-snake">Snake</a>
</p>

---

## 👋 About Me

你好，我是 **Nova**。我的研究关注 **自动驾驶场景生成、三维场景重建与闭环仿真测试**，希望让真实驾驶数据与生成模型共同服务于驾驶策略的训练、测试和改进。

- 🚗 **Generative Simulation & Policy Testing**：研究生成场景的交通合理性、策略响应与测试价值。
- 🎥 **Video-to-Interactive Scene**：探索行车视频重建、长时序场景表示与闭环测试之间的连接。
- 🧠 **Multi-agent Behavior Modeling**：关注交通行为生成、轨迹预测与不完整观测下的轨迹重建。

---

## 🛣️ OnSite Timeline

过去三届 **OnSite 自动驾驶算法挑战赛** 中，我持续参与场景生成与测试相关技术工作，并围绕赛事逐步推进从规则仿真到生成式场景与策略测试的完整技术链路。

### OnSite 3.0 · Rule-driven Scenario Generation

**[Onsite_rule_driven_model](https://github.com/Nova-chen151/Onsite_rule_driven_model)**

面向智能场景生成赛道构建规则驱动交通仿真 baseline，覆盖背景车辆的 **跟驰、换道、合流、分流与冲突交互** 等典型交通行为。

<p>
  <a href="https://github.com/Nova-chen151/Onsite_rule_driven_model">
    <img src="https://img.shields.io/badge/Code-Onsite__rule__driven__model-181717?style=flat-square&logo=github&logoColor=white" />
  </a>
</p>

### OnSite · Scenario Evaluation & Replay Testing

**[Onsite_Ego_Testing](https://github.com/Nova-chen151/Onsite_Ego_Testing)**

围绕生成场景构建离线回放与评测流程，将生成场景接入多个驾驶规划器，完成 **回放测试、指标计算、评分汇总与可视化分析**。

<p>
  <a href="https://github.com/Nova-chen151/Onsite_Ego_Testing">
    <img src="https://img.shields.io/badge/Code-Onsite__Ego__Testing-181717?style=flat-square&logo=github&logoColor=white" />
  </a>
</p>

### OnSite 4.0 · Unified Train-Test Scenario Generation

**[Onsite_Data-driven_Baseline](https://github.com/Nova-chen151/Onsite_Data-driven_Baseline)** ·
**[Onsite_UT2SG_Testing](https://github.com/Nova-chen151/Onsite_UT2SG_Testing)**

从数据驱动背景车行为生成进一步扩展到 **BV–AV 联合评测**，连接场景生成与自动驾驶策略闭环测试，逐步形成：

**Scenario Generation → Policy Testing → Evaluation**

<p>
  <a href="https://github.com/Nova-chen151/Onsite_Data-driven_Baseline">
    <img src="https://img.shields.io/badge/Code-Data--driven%20Baseline-181717?style=flat-square&logo=github&logoColor=white" />
  </a>

  <a href="https://github.com/Nova-chen151/Onsite_UT2SG_Testing">
    <img src="https://img.shields.io/badge/Code-UT2SG%20Testing-181717?style=flat-square&logo=github&logoColor=white" />
  </a>
</p>

### OnSite · 3D Scenario Generation Benchmark

**[OnSite 3DSG Benchmark](https://nova-chen151.github.io/Onsite3DSG-Benchmark.github.io/)**

进一步探索生成式驾驶场景如何从 **visual realism** 走向真正的 **policy testing**，关注场景的观测质量、交通保真度、策略响应与测试有效性。

> **Can generated driving scenarios become trustworthy policy tests?**

<p>
  <a href="https://nova-chen151.github.io/Onsite3DSG-Benchmark.github.io/">
    <img src="https://img.shields.io/badge/Project-Page-6366F1?style=flat-square" />
  </a>

  <a href="https://github.com/Nova-chen151/Onsite3DSG-Benchmark.github.io">
    <img src="https://img.shields.io/badge/Code-Repository-181717?style=flat-square&logo=github&logoColor=white" />
  </a>
</p>

---

## 📝 Selected Publications

### CDPT · AAAI 2026

**[Transferring Causal Driving Patterns for Generalizable Traffic Simulation with Diffusion-Based Distillation](https://ojs.aaai.org/index.php/AAAI/article/view/36970)**  
Yuhang Chen, Jie Sun, Jialin Fan, Jian Sun

面向跨域交通仿真的因果驾驶模式迁移与扩散蒸馏。

<p>
  <a href="https://ojs.aaai.org/index.php/AAAI/article/view/36970">
    <img src="https://img.shields.io/badge/Paper-AAAI%202026-3B82F6?style=flat-square" />
  </a>

  <a href="https://github.com/Nova-chen151/SIM-CDPT">
    <img src="https://img.shields.io/badge/Code-SIM--CDPT-181717?style=flat-square&logo=github&logoColor=white" />
  </a>

  <a href="https://nova-chen151.github.io/simCDPT.github.io/">
    <img src="https://img.shields.io/badge/Project-Page-6366F1?style=flat-square" />
  </a>
</p>

---

## 🐍 Contribution Snake

<p align="center">
  <picture>
    <source
      media="(prefers-color-scheme: dark)"
      srcset="https://raw.githubusercontent.com/Nova-chen151/Nova-chen151/output/github-contribution-grid-snake-dark.svg"
    />
    <source
      media="(prefers-color-scheme: light)"
      srcset="https://raw.githubusercontent.com/Nova-chen151/Nova-chen151/output/github-contribution-grid-snake.svg"
    />
    <img
      alt="GitHub contribution grid snake animation"
      src="https://raw.githubusercontent.com/Nova-chen151/Nova-chen151/output/github-contribution-grid-snake.svg"
    />
  </picture>
</p>

---

<p align="center">
  <b>AI for driving scenarios, driving scenarios for AI.</b><br/>
  <sub>AI 服务 AI · From scenario generation to trustworthy policy testing.</sub>
</p>

<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0%3A7AA2FF%2C55%3A8C8FF5%2C100%3A78C8E8&height=110&section=footer"
    width="100%"
    alt="footer"
  />
</p>
