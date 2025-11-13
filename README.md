# 魏雨飞 (Yufei Wei)

<div align="center">

🎓 **PhD Student @ Zhejiang University**  
🏫 **College of Control Science and Engineering**  
🤖 **3D Vision, World Model & Embodied AI Researcher**
<h3>🏠 <b>Homepage</b>: <a href="https://weiyufei0217.github.io/" target="_blank">weiyufei0217.github.io</a></h3>

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

<div align="center">

**© 2025 魏雨飞 (Yufei Wei)**  
*Last updated: November 2025*

</div>
