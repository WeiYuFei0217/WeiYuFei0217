# 魏雨飞 (Yufei Wei)

<div align="center">

<img src="profile_photo.jpg" alt="魏雨飞" width="250"/>

🎓 **PhD Student @ Zhejiang University**  
🏫 **College of Control Science and Engineering**  
🤖 **3D Vision, World Model & Embodied AI Researcher**

[![Email](https://img.shields.io/badge/Email-wyf00%40zju.edu.cn-blue)](mailto:wyf00@zju.edu.cn)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-Profile-green)](https://scholar.google.com/citations?user=68ftKf4AAAAJ)
[![GitHub](https://img.shields.io/badge/GitHub-WeiYuFei0217-black)](https://github.com/WeiYuFei0217)

</div>

---

## 📖 Biography

Hi! I'm Yufei Wei (魏雨飞), a Ph.D. student at the College of Control Science and Engineering, Zhejiang University, advised by Prof. Yue Wang and Prof. Rong Xiong. My research centers on 3D visual perception, world models, and embodied AI — I'm driven by the vision of enabling robots to genuinely understand and interact with the real world, not just move through it.

My earlier work focused on monocular visual odometry, Bird's-Eye View representations, and visual localization, published in journals and conferences including IEEE RA-L and IROS. These efforts addressed real-world challenges in reducing scale drift and achieving robust localization for mobile robots in complex environments. As a collaborator, I've also contributed to projects spanning learning-based navigation planning, multi-sensor fusion localization, and applications in  agricultural automation and medical robotics. Currently, I'm exploring world model construction and vision-and-language navigation, focusing on cross-modal integration through unified representations, and leveraging multimodal LLMs for scene understanding and navigation tasks.

During my undergraduate years, I led teams to three national championships in autonomous driving and robotics competitions, contributed to the PaddlePaddle open-source community, and developed a lightweight autonomous delivery vehicle. I also served as team leader for an intelligent ergonomic chair startup at Zexiang Li's Entrepreneurship Incubator in Shenzhen and spent time teaching at a primary school in Yulin, Guangxi. During my internship at Shenzhen InnoX Academy, I contributed to developing a semantic line segment mapping-based LiDAR-IMU SLAM system and obstacle avoidance algorithms for autonomous street sweeping vehicles. Whether in research or real-world deployment, I prioritize building systems that actually work over chasing theoretical elegance alone.

I'm always excited to collaborate, discuss ideas, and learn from others. If you're working on visual perception, world models, embodied AI, or anything that brings robots closer to understanding our world, let's chat! 🤖

---

## 📰 News

- **2025.11** | First-author preprint **Multi-cam Multi-map Visual Inertial Localization** released on arXiv, proposing a multi-camera multi-map visual-inertial localization system with causality-preserving evaluation metrics.

- **2025.09** | First-author preprint **BEV-ODOM2** released on arXiv, exploring PV-BEV fusion and dense flow supervision for BEV-based 3-DoF monocular visual odometry.

- **2025.02** | First-author paper **BEV-DWPVO** accepted by **IEEE RA-L**, achieving best average RTE with superior scale consistency using BEV representation and differentiable weighted Procrustes solver.

- **2024.10** | First-author paper **BEV-ODOM** published at **IROS 2024**, demonstrating that BEV representation alone can achieve low scale drift in monocular visual odometry.

---

## 🎓 Education

### Zhejiang University (浙江大学)
**Ph.D. Student** | Control Science and Engineering | 2022.09 - 2027.06 (Expected)  
Advisor: Prof. Yue Wang (王越教授), Prof. Rong Xiong (熊蓉教授)  
Research Interests: 3D Visual Perception, World Models, Embodied AI

### Huazhong University of Science and Technology (华中科技大学)
**B.Eng.** | Electronic Information Engineering | 2018.09 - 2022.06  
School of Electronic Information and Communications

---

## 📚 Publications

> 📑 **[My Google Scholar](https://scholar.google.com/citations?user=68ftKf4AAAAJ)**

### First-Author Publications

#### 📄 BEV-ODOM2: Enhanced BEV-based Monocular Visual Odometry with PV-BEV Fusion and Dense Flow Supervision for Ground Robots

<div align="center">
<img src="paper_images/bev_odom2.jpg" alt="BEV-ODOM2" width="600"/>
</div>

**Authors:** **Yufei Wei**, Wangtao Lu, Sha Lu, Chenxiao Hu, Fuzhang Han, Rong Xiong, Yue Wang  
**Venue:** IEEE Transactions on Intelligent Transportation Systems (T-ITS) - **Under Review**  
**Description:** BEV-ODOM2 introduces dense BEV optical flow supervision constructed directly from pose ground truth and PV-BEV dual-branch fusion to address sparse supervision and information loss without additional annotations. Achieving 40% RTE improvement over existing BEV methods, it delivers state-of-the-art performance across multiple datasets while maintaining superior scale consistency. **(Under Review)**  
[[Paper]](https://arxiv.org/abs/2509.14636)

---

#### 📄 BEV-DWPVO: BEV-based Differentiable Weighted Procrustes for Low Scale-drift Monocular Visual Odometry on Ground

<div align="center">
<img src="paper_images/bev_dwpvo.jpg" alt="BEV-DWPVO" width="600"/>
</div>

**Authors:** **Yufei Wei**, Sha Lu, Wangtao Lu, Rong Xiong, Yue Wang  
**Venue:** IEEE Robotics and Automation Letters (RA-L), 2025  
**Description:** BEV-DWPVO leverages unified metric-scaled BEV representation and differentiable weighted Procrustes solver to address scale drift in monocular visual odometry. By simplifying pose estimation to 3-DoF and training end-to-end with only pose supervision, it achieves best average RTE of 8.67% and 6.92% on NCLT and Oxford datasets, delivering superior scale consistency without requiring depth estimation or segmentation supervision.  
[[Paper]](https://ieeexplore.ieee.org/abstract/document/10909180) [[Code]](https://github.com/WeiYuFei0217/BEV-DWPVO)

---

#### 📄 BEV-ODOM: Reducing Scale Drift in Monocular Visual Odometry with BEV Representation

<div align="center">
<img src="paper_images/bev_odom.jpg" alt="BEV-ODOM" width="600"/>
</div>

**Authors:** **Yufei Wei**, Sha Lu, Fuzhang Han, Rong Xiong, Yue Wang  
**Venue:** 2024 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), pp. 349-356  
**Description:** BEV-ODOM is the first to demonstrate that BEV representation alone, without segmentation or auxiliary tasks, can achieve low scale drift in monocular visual odometry. Using correlation-based feature extraction and 3-DoF pose regression with only pose supervision, it reveals that scale consistency originates from BEV's inherent metric-scaled grid structure rather than side-tasks, providing a simpler and more interpretable approach.  
[[Paper]](https://ieeexplore.ieee.org/abstract/document/10801996)

---

#### 📄 Multi-cam Multi-map Visual Inertial Localization: System, Validation and Dataset

<div align="center">
<img src="paper_images/multi_cam.jpg" alt="Multi-cam Multi-map VIL" width="600"/>
</div>

**Authors:** **Yufei Wei**, Fuzhang Han, Yanmei Jiao, Zhuqing Zhang, Yiyuan Pan, Wenjun Huang, Li Tang, Huan Yin, Xiaqing Ding, Rong Xiong, Yue Wang  
**Venue:** IEEE Transactions on Field Robotics (T-FR) - **Under Review**  
**Description:** Robot control requires causal pose estimates without retroactive corrections. This work proposes a multi-camera filter-based VILO system enabling operation across multiple isolated maps without overlap requirements. Deterministic initialization and IMU-aided 2-point minimal solvers maintain robustness under 80%+ outlier rates. To validate the system under long-term appearance changes, we collect a 9-month, 55km campus dataset and propose causality-preserving evaluation metrics aligned with control requirements.  
[[Paper]](https://arxiv.org/abs/2412.04287) [[Code]](https://github.com/WeiYuFei0217/BEV-DWPVO)

---

### Co-authored Publications

#### 📄 Learning to Tune a Mobile Robot Planner: Formulation, Architecture, and Sim-to-Real

<div align="center">
<img src="paper_images/LWT_JFR2026.jpg" alt="Learning to Tune" width="600"/>
</div>

**Authors:** Wangtao Lu, Wei Zhang, **Yufei Wei**, Rong Xiong, Chaoqun Wang, Yue Wang  
**Venue:** Journal of Field Robotics - **Under Review**  
**Description:** This work resolves the architectural bottleneck of learning-based planner tuning by proposing a multi-rate hierarchical framework that decouples navigation into coordinated low-frequency tuning (1Hz), mid-frequency planning (10Hz), and high-frequency control (50Hz) loops. The Cyclic Co-Training strategy enables stable learning of coupled policies, while the Terrain-Adaptive Controller achieves robust zero-shot sim-to-real transfer by maintaining consistent tracking performance across diverse terrains, outperforming state-of-the-art auto-tuning and end-to-end methods. **(Under Review)**

---

#### 📄 Human-Guided Robotic-Assistance Handheld Continuum Medical Robot System

<div align="center">
<img src="paper_images/WF_IROS2025.jpg" alt="HRHC" width="600"/>
</div>

**Authors:** Fei Wang, Changhao Luo, Zexi Zhao, Pingyu Xiang, **Yufei Wei**, Ke Qiu, Yufei Wei, Yue Wang, Rong Xiong and Haojian Lu  
**Venue:** 2025 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) - Accepted  
**Description:** HRHC presents a human-guided handheld continuum medical robot system that bridges the gap between manual instruments and fully robotic solutions for minimally invasive surgery. Featuring modular design with integrated binocular vision for real-time depth perception, IMU-driven intuitive control, and millimeter-level dexterity in confined spaces, it extends surgeon capabilities while maintaining portability and natural operation. My contribution: sensor system architecture design and software deployment for the multi-modal perception platform.

---

#### 📄 SeqBEV: Bayesian Sequential Localization Using BEV LiDAR Map

<div align="center">
<img src="paper_images/LS_ACAR2025.jpg" alt="SeqBEV" width="600"/>
</div>

**Authors:** Sha Lu, **Yufei Wei**, Rong Xiong, Yue Wang  
**Venue:** 2025 IEEE International Conference on Real-time Computing and Robotics (RCAR), pp. 407-412  
**Description:** SeqBEV proposes a robust sequential LiDAR localization framework using compact BEV map representation and Bayesian filtering for challenging sparse map scenarios (50m node spacing). By employing NCC-based template matching for uncertainty-aware pose distribution estimation and recursive Bayesian fusion for temporal consistency, it achieves 23.33% improvement in Recall@1 and reduces localization errors to 0.62m (50th percentile) on the NCLT dataset, demonstrating superior robustness compared to single-shot and descriptor-based methods in feature-insufficient environments.  
[[Paper]](https://ieeexplore.ieee.org/abstract/document/11139435)

---

#### 📄 Reinforcement Learning for Adaptive Planner Parameter Tuning: A Perspective on Hierarchical Architecture

<div align="center">
<img src="paper_images/LWT_ICRA2025.jpg" alt="RL Planner Tuning" width="600"/>
</div>

**Authors:** Wangtao Lu, **Yufei Wei**, Jiadong Xu, Wenhao Jia, Liang Li, Rong Xiong, Yue Wang  
**Venue:** 2025 IEEE International Conference on Robotics and Automation (ICRA), pp. 3883-3889  
**Description:** This work proposes a hierarchical architecture integrating low-frequency parameter tuning (1Hz), mid-frequency planning (10Hz), and high-frequency control (50Hz) for autonomous navigation. An RL-based feedback controller is introduced to minimize tracking errors that cannot be resolved through parameter tuning alone. Through alternating training between the parameter tuning network and controller, the method achieves 98% success rate and 10.2s completion time on BARN Challenge, winning first place. Real-world experiments demonstrate 100% success rate with superior tracking accuracy.  
[[Paper]](https://ieeexplore.ieee.org/abstract/document/11128541)

---

#### 📄 Towards Agricultural Vehicle Autonomy: Adaptive PID Control for Precise Path Tracking with Visual-Inertial Localization

<div align="center">
<img src="paper_images/ZDK_CCC2025.jpg" alt="Agricultural Vehicle" width="600"/>
</div>

**Authors:** Dongkun Zhang, **Yufei Wei**, Xujiong Feng, Jinpeng Gan, Zhi Huang, Huanyu Jiang, Zidong Yang, Daxu Zhao, Rong Xiong, Yue Wang  
**Venue:** 2025 44th Chinese Control Conference (CCC), pp. 4630-4636  
**Description:** This work presents a cost-effective autonomous agricultural vehicle system using visual-inertial localization to replace expensive RTK-GPS. The proposed modular design integrates a quad-camera setup with IMU for robust pose estimation and employs an adaptive PID controller based on FOPTD model for precise path tracking. Field experiments demonstrate errors below 4.38cm and over 90% trajectory points within 7.5cm threshold using vision-only localization, validating its feasibility for practical agricultural automation.  
[[Paper]](https://ieeexplore.ieee.org/abstract/document/11178414)

---

#### 📄 Demonstration Data-Driven Parameter Adjustment for Trajectory Planning in Highly Constrained Environments

<div align="center">
<img src="paper_images/LWT_RAL2025.jpg" alt="Demonstration Data-Driven" width="600"/>
</div>

**Authors:** Wangtao Lu, Lin Chen, Yunkai Wang, **Yufei Wei**, Zifei Wu, Rong Xiong, Yue Wang  
**Venue:** IEEE Robotics and Automation Letters (RA-L), 2024  
**Description:** This work introduces a demonstration data-driven RL framework using CGAN discriminator to bridge trajectory-space demonstrations and parameter-space learning. Combined with asynchronous controller architecture, the method achieves 5× faster convergence than pure RL (0.6M vs 3M steps) and secures first place in BARN Challenge, with strong sim-to-real transfer capability validated in real-world experiments.  
[[Paper]](https://ieeexplore.ieee.org/abstract/document/10749994)

---

#### 📄 VIVO: A Visual-Inertial-Velocity Odometry with Online Calibration in Challenging Condition

<div align="center">
<img src="paper_images/HFZ_IROS2024.jpg" alt="VIVO" width="600"/>
</div>

**Authors:** Fuzhang Han, Shenhan Jia, Jiyu Yu, **Yufei Wei**, Wenjun Huang, Yue Wang, Rong Xiong  
**Venue:** 2024 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), pp. 8571-8578  
**Description:** VIVO proposes a tightly coupled visual-inertial-velocity odometry with online extrinsic calibration, directly fusing high-frequency velocity measurements into MSCKF-based VIO. Validated on both wheeled robots and high-speed quadrupeds (up to 3 m/s), it achieves superior robustness in challenging conditions with lower ATE than OpenVINS/MSF and 2× efficiency over ORB-SLAM3.  
[[Paper]](https://ieeexplore.ieee.org/abstract/document/10801486)

---

#### 📄 OTVIC: A Dataset with Online Transmission for Vehicle-to-Infrastructure Cooperative 3D Object Detection

<div align="center">
<img src="paper_images/ZH_IROS2024.jpg" alt="OTVIC" width="600"/>
</div>

**Authors:** He Zhu, Yunkai Wang, Quyu Kong, **Yufei Wei**, Xunlong Xia, Bing Deng, Rong Xiong, Yue Wang  
**Venue:** 2024 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), pp. 10732-10739  
**Description:** OTVIC presents the first real-world V2I cooperative perception dataset with online transmission, capturing dynamic delays, high-speed scenarios (70-110 km/h), and bandwidth constraints in highway environments. The proposed LfFormer framework achieves robust late fusion by encoding infrastructure perception results as transformer queries, delivering 2.3% mAP improvement while maintaining low communication bandwidth and strong robustness to delays and packet loss.  
[[Paper]](https://ieeexplore.ieee.org/abstract/document/10802656)

---

#### 📄 Adapting for Calibration Disturbances: A Neural Uncalibrated Visual Servoing Policy

<div align="center">
<img src="paper_images/YHX_ICRA2024.jpg" alt="NUVS" width="600"/>
</div>

**Authors:** Hongxiang Yu, Anzhe Chen, Kechun Xu, Dashun Guo, **Yufei Wei**, Zhongxiang Zhou, Xuebo Zhang, Yue Wang, Rong Xiong  
**Venue:** 2024 IEEE International Conference on Robotics and Automation (ICRA), pp. 17417-17423  
**Description:** NUVS addresses the labor-intensive calibration challenge in industrial visual servoing by proposing a neural uncalibrated policy that adapts to camera calibration disturbances. By estimating calibration embeddings from past observations to modulate the neural controller and leveraging PBVS supervision in simulation, it achieves both the disturbance adaptation of classical methods and the large convergence basin of learning-based approaches, outperforming IBUVS under calibration disturbances with large initial pose offsets.  
[[Paper]](https://ieeexplore.ieee.org/abstract/document/10610364)

---

## 🔬 Research Projects

### 🚀 ZJU & xx Research Institute - Legged xx Exploration Robot Project
Designed and led the development of a full-stack perception and navigation system for autonomous exploration in complex terrain. Built an integrated multi-sensor stack (LiDAR, stereo cameras, IMU) with a robust calibration pipeline, and implemented laser-inertial / visual-inertial localization together with deep learning–based stereo matching for dense 3D reconstruction. On top of this stack, developed a lightweight terrain analysis and path-planning framework tailored to resource-constrained platforms, operating directly on point clouds to extract ground planes, characterize terrain geometry (concavities/convexities), identify traversable regions, and generate optimized paths via graph-based planning. Validated the system in 100+ automated test scenarios, demonstrating reliable navigation performance in cluttered, highly irregular environments.

*\* xx: redacted for confidentiality*

---

### 🌾 Provincial Major R&D Program - Agricultural Automation System
Designed and led the development of a vision-only navigation system for agricultural machinery, covering the complete sensing architecture, perception stack, and visual–inertial odometry framework. Built a four-camera and IMU perception module with a dedicated vibration-attenuating structure and implemented a multi-view visual–inertial fusion system optimized for low-texture, high-vibration agricultural environments. Integrated the system with an error-compensation tracking controller and demonstrated centimeter-level trajectory accuracy in rice-transplanter farmland trials when compared against RTK-INS ground truth.

---

### 🦾 ZJU & ZJH (Zhejiang Humanoid Robot Innovation Center) – Wheeled Humanoid Perception & Navigation System
Developed the perception and navigation subsystem for a wheeled humanoid robot platform. Built a vision-centric BEV representation from multi-camera inputs to generate dense costmaps and 3-DoF pose estimates. Integrated the perception layer with A* global planning and TEB local optimization, enabling reliable, obstacle-aware visual navigation for the humanoid robot's wheeled base.

---

### 🚙 ZJU & Alibaba - Autonomous Driving Data Collection Platform
Designed the perception hardware architecture for the autonomous driving data collection vehicle, including structural design and vehicle-level integration of the quad-camera, LiDAR, IMU, GPS/RTK, and V2X sensing modules. Implemented the multi-sensor calibration workflow and deployed the multi-view visual–IMU–GPS odometry algorithms on the vehicle platform to ensure accurate and reliable motion estimation. Conducted data consistency checks and ground-truth alignment to support high-quality multi-modal dataset generation.

---

### 🐕 ZJU & SDU - Quadruped Robot Swarm Project
Deployed stereo-vision–based 3D reconstruction on quadruped platforms and built a BEV-centric spatial representation for robust perception in multi-robot settings. Implemented BEV odometry to generate reliable pose estimates for downstream planning modules, enabling coordinated motion within the robot swarm.

---

## 💼 Industrial Experience

### 🏢 Shenzhen InnoX Academy - Autonomous Driving Center (2022.2 - 2022.9)
Built a semantic line segment mapping system for autonomous street sweeping vehicles in urban environments. The system uses deep semantic segmentation to extract static linear landmarks like lamp posts and road markings. By representing these landmarks as compact line segments rather than dense point clouds, it filters out dynamic traffic participants, handles varying weather and lighting conditions, and enables real-time LiDAR-IMU SLAM on resource-constrained onboard computers.

---

## 🏆 竞赛获奖、专利与项目

### 🏆 竞赛获奖

- **全国冠军&队长** - 2021年全国大学生工程实践与创新能力大赛 智能网联汽车设计赛道
- **全国冠军&队长** - 第十五届全国大学生智能汽车竞赛 百度智能驾驶组
- **全国冠军&队长** - 第三届中国高校智能机器人创意大赛 ROS无人机组
- **全国一等奖&队长** - 第二十三届中国机器人及人工智能大赛 无人驾驶挑战赛 & 深度学习智能车（双赛项）
- **省赛一等奖&队长** - 2021"西门子杯"中国智能制造挑战赛 离散行业自动化
- **冠军&队长** - 2021"微派·种子杯"创新性软件编程PK赛
- **冠军&队长** - 华中科技大学第十四届瑞萨杯智能车大赛
- **二等奖** - 全国大学生电工数学建模、MathorCup高校数学建模、"华中杯"大学生数学建模

### 📜 发明专利

- **CN202411248996.8** - 基于鸟瞰视角表征的单目视觉里程计系统及其方法（第一学生发明人）
- **CN202411981529.6** - 基于鸟瞰视角表征和可微分加权Procrustes求解器的单目视觉里程计方法和系统（第一学生发明人）
- **CN202110568966.5** - 基于双目视觉和深度学习的车辆避障方法与电子设备（第一学生发明人）
- **CN202110971772.X** - 一种基于模仿学习和强化学习的高速运动车辆控制方法（第一学生发明人）
- **CN202110979800.2** - 一种双阶段自动驾驶车辆调头轨迹规划方法（第一学生发明人）

### 🌱 本科生创业项目

- **省级大创** - "基于双目视觉和深度学习的轻量级无人配送车"（初创项目，优秀结题）

---

## 🌟 Beyond Research

### 🏫 广西玉林-古城小学支教

2019 年盛夏，我随支教队来到广西玉林古城小学，兼任英语老师和班主任，在潮湿闷热与忽晴忽雨的天气里，与几十个性格迥异的孩子一起度过了难忘的三周。最初从慌乱铺床、紧张上课，到熟悉校园每个角落、能够从容站上讲台，我在备课、带班、家访和无数次"崩溃-重整"的循环中，慢慢学会了承担、耐心与真正意义上的陪伴。孩子们一句"老师，你讲得好有意思"、几份终于不再抄袭的作业,和他们在暴雨后操场上肆意奔跑的身影，始终是我跨过高烧、争执与自我怀疑的力量来源。

小时候看过一部关于拐卖的纪录片，从那时起，我便一直怀揣着想要解决拐卖的问题。这个梦想至今仍遥远，但在这所偏远的山村小学，在 2019 年那个潮湿的夏天，我第一次真切意识到：教育与守护是预防伤害的第一道防线，也是为孩子们在深山穹顶上打开的一扇天窗。离开古城小学后，我仍常想起那些在黄昏灯光下写作业、在最后一晚的月光下与我道别的孩子们——愿我当时笨拙却真诚的努力，能在他们的人生里留下哪怕一点点温暖而长久的光。

---

### 💼 创业经历

在本科阶段，我组建并领导了一支共计11人的创始团队，发起了一款智能人体工学椅项目，致力于解决久坐带来的腰背健康问题。我们目标是通过"可感知、会学习、能主动支撑"的椅背系统，提供超越传统座椅的个性化支撑体验。我主导了整体产品规划与技术路线设计，从市场调研、用户需求分析，到功能定义、系统架构设计与项目实施，全面推动了方案的落地和团队的协同。

我们的核心技术结合了压力传感矩阵、背部传感器与机器学习算法，能够精准识别用户身份、臀部位置与坐姿，并据此自动调整支撑力度。我们的支撑系统采用机械推杆与多分区气囊组合，机械部分负责大范围调节，气囊则提供精细调整，支持全自动、半自动和手动调节。通过App与实体按键的交互，系统能不断学习并优化用户习惯，实现个性化的追背与腰骶骨支撑效果。在此过程中，我带领团队运用第一性原理分析问题，并通过最小子系统迭代验证方案，成功完成了三代功能样机，涵盖了从结构设计、控制电路到算法验证、供应链与专利布局的完整流程，并顺利获得了天使轮融资机会。

---

<div align="center">

**© 2025 魏雨飞 (Yufei Wei)**  
*Last updated: November 2025*

</div>
