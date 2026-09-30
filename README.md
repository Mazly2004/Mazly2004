<!-- Animated header -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Oliver%20Mazorodze&fontSize=48&fontColor=ffffff&desc=Robotics%20%C2%B7%20State%20Estimation%20%C2%B7%20Perception&descAlignY=65&animation=fadeIn" width="100%"/>

<!-- Typing animation -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=36BCF7&center=true&vCenter=true&width=600&lines=Building+an+in-pipe+inspection+robot+%F0%9F%A4%96;Kalman+filters+%7C+EKF+%7C+Sensor+fusion;ROS+2+%2B+C%2B%2B+%2B+Deep+Learning;AI+%26+ML+%40+University+of+Zimbabwe" />
</p>

## 🤖 About me
AI & ML student at the University of Zimbabwe, focused on **robotics**:
state estimation, sensor fusion, and perception for autonomous systems.

## 🔧 Currently building
An **in-pipe inspection robot** that knows where it is and what it's looking at:

```mermaid
flowchart LR
    IMU[IMU] --> EKF[EKF Localization]
    ODOM[Wheel odometry] --> EKF
    TETHER[Tether length] --> EKF
    CAM[Camera] --> DL[Defect detection<br/>deep learning]
    EKF -->|position ± uncertainty| MAP[Defect map<br/>crack at 23.4 m ± 0.2 m]
    DL --> MAP
```

## 🛠️ Tech
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=for-the-badge&logo=ros&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

## 🤝 Team projects
- **[Esp32HydroponicProject](https://github.com/Mazly2004/Esp32HydroponicProject)**: ESP32 hydroponics monitoring (with @KeithAGang). I worked on …
- **[SwamoraPlantIdentification](https://github.com/Mazly2004/SwamoraPlantIdentification)**: plant identification (with @KeithAGang). I worked on …

## 🐍 Contributions
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Mazly2004/Mazly2004/output/github-snake-dark.svg" />
  <img alt="snake" src="https://raw.githubusercontent.com/Mazly2004/Mazly2004/output/github-snake.svg" />
</picture>

## 📫 Contact
[Email](mailto:olivermazorodze1@gmail.com) · [LinkedIn](YOUR_LINKEDIN_URL)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=100&section=footer" width="100%"/>
