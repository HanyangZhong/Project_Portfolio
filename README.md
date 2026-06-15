---

layout: page
title: 项目展示
permalink: /projects/
---------------------

# 项目展示

本页面整理了本人博士阶段及相关研究工作中的代表性项目，用于展示论文背后的真实机器人系统、实验平台与项目图片。

本人研究主要围绕 **具身智能、接触丰富操作、灵巧手、力觉感知、多模态机器人学习、遥操作示教、模仿学习与机器人空间感知** 展开。

---

## 代表性项目

### DexRemo：面向接触丰富移除操作的力感知灵巧手平台

**关键词：** 灵巧操作｜力觉感知｜接触丰富操作｜机器人硬件｜真实机器人系统

**对应论文：**
*DexRemo: A Wrist-Frame Fingertip Force Sensing Hand Platform for Contact-Rich Removal Manipulation*
IEEE Transactions on Robotics, 二轮审稿中, 2026.

<p align="center">
  <img src="/assets/img/dexremo/dexremo_1.png" width="45%">
  <img src="/assets/img/projects/dexremo_hand.jpg" width="45%">
</p>

<p align="center">
  <img src="/assets/img/projects/dexremo_force_sensor.jpg" width="45%">
  <img src="/assets/img/projects/dexremo_experiment.jpg" width="45%">
</p>

DexRemo 是一个面向接触丰富移除操作任务的力感知灵巧手平台。系统集成了自研指尖力传感器、腕部坐标系力表示、嵌入式控制、机械结构设计与真实机器人操作实验。

**本人贡献：**

* 参与灵巧手平台与指尖力传感器设计。
* 完成传感器标定、信号采集与软硬件集成。
* 参与接触丰富移除操作实验设计与真实机器人验证。
* 支撑系统评测、算法验证与论文撰写。

---

### 接触丰富双臂模仿学习系统

**关键词：** 双臂操作｜模仿学习｜遥操作示教｜力觉感知｜多模态数据

**对应论文：**
*Hidden Force-Regime Coverage for Contact-Rich Bimanual Imitation Learning*
Conference on Robot Learning, 审稿中, 2026.

<p align="center">
  <img src="/assets/img/projects/bimanual_platform.jpg" width="45%">
  <img src="/assets/img/projects/teleoperation_demo.jpg" width="45%">
</p>

<p align="center">
  <img src="/assets/img/projects/force_regime.jpg" width="45%">
  <img src="/assets/img/projects/policy_rollout.jpg" width="45%">
</p>

该项目研究接触丰富双臂操作任务中的隐式力域覆盖问题，结合双臂遥操作平台、多模态传感器、示教数据采集、模仿学习训练与真实机器人策略部署。

**本人贡献：**

* 独立搭建并调试双臂遥操作平台。
* 开发视觉、力觉与本体感觉多模态数据采集流程。
* 完成力觉传感系统设计与集成。
* 支持模仿学习策略在真实机器人上的部署与验证。

---

### StrucLine-SLAM：面向结构主导环境的轻量级全几何 SLAM 系统

**关键词：** SLAM｜线特征｜几何建图｜机器人感知｜结构化环境

**对应论文：**
*StrucLine-SLAM: A Lightweight and Fully Geometric SLAM System for Structure-Dominant Environments*
Robotics and Autonomous Systems, 审稿中, 2026.

<p align="center">
  <img src="/assets/img/projects/strucline_pipeline.jpg" width="45%">
  <img src="/assets/img/projects/strucline_mapping.jpg" width="45%">
</p>

<p align="center">
  <img src="/assets/img/projects/strucline_dataset.jpg" width="45%">
  <img src="/assets/img/projects/strucline_comparison.jpg" width="45%">
</p>

StrucLine-SLAM 是一个面向走廊、车间、光伏场景等结构主导环境的轻量级几何 SLAM 系统。该系统利用线特征和结构几何约束，在低纹理场景中提升定位与建图鲁棒性。

**本人贡献：**

* 提出基于线特征约束的几何 SLAM 框架。
* 开发结构感知的特征匹配、建图与优化模块。
* 在公开数据集和自采结构化场景中完成系统验证。
* 构建用于结构化环境评测的新 SLAM 数据集。

---

### MLLM-Fabric：多模态大语言模型驱动的布料分拣机器人系统

**关键词：** 多模态大语言模型｜机器人感知｜布料操作｜视觉语言推理｜数据采集

**对应论文：**
*MLLM-Fabric: Multimodal Large Language Model-Driven Robotic Framework for Fabric Sorting and Selection*
IEEE Robotics and Automation Letters, 2025.

<p align="center">
  <img src="/assets/img/projects/mllm_fabric_framework.jpg" width="45%">
  <img src="/assets/img/projects/fabric_dataset.jpg" width="45%">
</p>

<p align="center">
  <img src="/assets/img/projects/fabric_prompting.jpg" width="45%">
  <img src="/assets/img/projects/fabric_robot_demo.jpg" width="45%">
</p>

该项目探索多模态大语言模型在布料分拣与机器人选择任务中的应用，将视觉感知、语言推理、提示词设计、数据采集与机器人决策相结合。

**本人贡献：**

* 参与多模态布料数据采集。
* 支持模型微调与实验评估。
* 设计面向推理的问题与提示词。
* 作为 ICRA 2026 poster presenter 展示该工作。

---

### LLM-SAP：基于情境感知的大语言模型机器人规划

**关键词：** 大语言模型｜情境感知｜机器人规划｜人机交互｜安全决策

**对应论文：**
*LLM-SAP: Large Language Models Situational Awareness-Based Planning*
IEEE ICME Workshops, 2024.

<p align="center">
  <img src="/assets/img/projects/llm_sap_framework.jpg" width="45%">
  <img src="/assets/img/projects/llm_sap_scenarios.jpg" width="45%">
</p>

该项目研究大语言模型在机器人情境感知与任务规划中的应用，关注上下文理解、任务推理与安全决策能力。

**本人贡献：**

* 参与规划框架设计。
* 设计情境感知测试场景与评估流程。
* 参与系统验证与论文撰写。

---

### FENet：面向自动驾驶车道线检测的视觉感知网络

**关键词：** 计算机视觉｜车道线检测｜自动驾驶｜深度学习

**对应论文：**
*FENet: Focusing Enhanced Network for Lane Detection*
IEEE ICME, Oral Paper, 2024.

<p align="center">
  <img src="/assets/img/projects/fenet_framework.jpg" width="45%">
  <img src="/assets/img/projects/fenet_results.jpg" width="45%">
</p>

FENet 是一个面向复杂道路场景的车道线检测网络，旨在提升车道线特征表达与检测鲁棒性。

**本人贡献：**

* 参与模型设计与实验评估。
* 支持基准测试、结果可视化与论文撰写。

---

## 项目能力总结

通过上述项目，本人积累了以下方面的系统经验：

* 真实机器人平台搭建与系统集成
* 灵巧手与力觉传感器设计
* 多模态传感器同步与数据采集
* 遥操作示教与模仿学习
* 机器人学习策略部署与验证
* SLAM 与几何机器人感知
* 视觉-语言-动作模型与具身智能系统
* 机器人软硬件协同设计

---

## 图片展示

<p align="center">
  <img src="/assets/img/projects/gallery_01.jpg" width="30%">
  <img src="/assets/img/projects/gallery_02.jpg" width="30%">
  <img src="/assets/img/projects/gallery_03.jpg" width="30%">
</p>

<p align="center">
  <img src="/assets/img/projects/gallery_04.jpg" width="30%">
  <img src="/assets/img/projects/gallery_05.jpg" width="30%">
  <img src="/assets/img/projects/gallery_06.jpg" width="30%">
</p>

---

## 联系方式

个人主页：https://hanyangzhong.github.io/
Google Scholar：[Google Scholar Profile](https://scholar.google.com/citations?user=6cbhsRMAAAAJ)
GitHub：https://github.com/HanyangZhong
