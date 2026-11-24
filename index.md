---
layout: homepage
---

## About Me

I am a senior undergraduate student in [**Civil and Environmental Engineering**](https://civil.yonsei.ac.kr/civil/index.do) at **Yonsei University**, Seoul. Before joining Yonsei, I studied **Information and Communication Engineering** at **Hankuk University of Foreign Studies (HUFS)**.

I build and race small autonomous vehicles in the Yonsei autonomous-driving club **YAX**, and I want to bring that hands-on robotics experience to construction sites: GPS-poor, cluttered environments that change every day. My goal is robots that can **see** (camera / LiDAR perception, depth estimation, SLAM) and **act** (autonomous navigation, learned manipulation) in the field.

## Research Interests

- **Robot Perception for Construction Sites:** monocular depth estimation, sensor fusion, LiDAR / visual SLAM, 3D detection of equipment and structures.
- **Mobile Robot Autonomy:** localization, planning and control for wheeled and legged robots doing site patrol, inspection and equipment tracking.
- **Learning-based Task Automation:** imitation learning and VLA policies for manipulation, autonomous construction equipment, and links to BIM / digital twins.

## Awards

- **Bronze Prize, Student Technology Category**, 4th MAGP (Minicar Autonomous Grand Prix), RoboRacer class, Gifu University, Japan, Nov. 2026. Team leader; reached the final 8 (joint 5th).
- **Encouragement Prize (KAIA President's Award, KRW 500,000)**, 2026 Crowdsourced Data Hackathon (hosted by the Ministry of Land, Infrastructure and Transport and KAIA), Nov. 2026. Team leader.

## Projects

**MAGP RoboRacer: 1/10-Scale Autonomous Racing Car**
- **Period:** Sep. 2026 - Nov. 2026
- **Role:** Team Leader, lead for vehicle hardware, software and algorithms
- Ported a ROS 2 driving stack onto a Traxxas 1/10 chassis with VESC 6, 2D LiDAR, IMU and wheel encoders, running fully onboard on an NVIDIA Jetson Orin Nano Super.
- LiDAR scan-matching particle filter (AMCL) fused with odometry for localization; Pure Pursuit waypoint following with per-surface parameter sets.
- Re-tuned the VESC FOC speed loop and braking logic; designed an SSH-based, server-driven remote control panel with E-stop and dead-man switch.
- Code: [YAX3_F1T_TEAM2](https://github.com/ixiivi/YAX3_F1T_TEAM2)

**YAX F1Tenth Module 2 Team (3rd cohort)**
- **Period:** 2026 - Present
- **Role:** Team Leader (6 members)
- Building and wiring a 1/10 F1Tenth platform, setting up the Jetson software environment, and running the team's schedule, task board and development log.

**2026 Crowdsourced Data Hackathon: Drone-Imagery Change Detection** (Encouragement Prize)
- **Period:** Nov. 2026
- **Role:** Team Leader, Team YAXXX (2 members)
- Proposed and demoed a pipeline that detects new or changed buildings and roads from crowdsourced drone imagery against digital maps, and reconstructs suspicious buildings as LoD2 3D models to estimate height and floors for illegal-structure inspection in mountain and state-owned land.

**Mars Relocation Support Platform (iOS Application)**
- **Period:** Mar. 2025 - Jun. 2025
- **Role:** iOS Developer
- A concept iOS app with logistics tracking and user management for a fictional AI-agent relocation to Mars.

## Paper Study Talks

- **PTC-Depth:** Pose-Refined Monocular Depth Estimation with Temporal Consistency (monocular camera + wheel odometry for metric depth), 2026.
- **ACT / ALOHA:** Learning Fine-Grained Bimanual Manipulation with Low-Cost Hardware (action chunking for imitation learning), 2026.

## Skills

- **Programming:** Python, C/C++, Java, Swift, Linux, Git
- **Robotics:** ROS 2, NVIDIA Jetson, 2D LiDAR, IMU, VESC
- **Civil / Design:** BIM (Autodesk Navisworks: clash detection, 4D simulation), Ansys Mechanical

## News

- **[Nov. 2026]** Won the Bronze Prize (Student Technology Category) at the 4th MAGP RoboRacer class in Gifu, Japan.
- **[Nov. 2026]** Won the Encouragement Prize at the 2026 Crowdsourced Data Hackathon.
- **[2026]** Leading Module 2 of the 3rd YAX F1Tenth cohort; preparing the camera lane-detection task for KRoC 2027.
