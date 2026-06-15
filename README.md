<div align="center">


### 🤖 Robotics Software Engineer | System Integration

**AI의 출력을 실제 로봇의 행동과 서비스로 연결하는 엔지니어**

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=2E9EF7&center=true&vCenter=true&width=600&lines=Connecting+AI+to+Real+Robot+Actions;Multi-Robot+Fleet+Management;ROS2+%7C+Nav2+%7C+Embedded+Systems;From+Perception+to+Motion)](https://git.io/typing-svg)

</div>

---

## 🎯 What I'm Building Toward

> 로봇이 실제 현장에서 동작하려면 AI 추론, 하드웨어 제어, 서비스 레이어가  
> 끊김 없이 연결되어야 합니다. 저는 그 **연결 지점**을 설계하고 구현합니다.

- 🤖 멀티로봇 시스템에서 신뢰할 수 있는 자율 행동 구현
- 🔗 AI 모델의 출력을 실시간 로봇 제어로 변환하는 미들웨어 설계
- 🏭 현장 투입 가능한 로봇 서비스 아키텍처

  
## 🧭 About Me

```python
class RoboticsEngineer:
    def __init__(self):
        self.role = "System Integration Engineer"
        self.focus = "AI 출력 → 로봇 행동/서비스 연결"
        self.location = "South Korea 🇰🇷"

    def what_i_do(self):
        return [
            "멀티로봇 함대 관제 시스템 설계",
            "ROS2 기반 자율주행 인프라 구축",
            "임베디드 ↔ AI ↔ 웹 서비스 통합",
        ]

    def philosophy(self):
        return "인지(Perception)에서 동작(Motion)까지, 끝까지 연결한다"
```

---

## 🛠️ Tech Stack

### Robotics & AI
![ROS2](https://img.shields.io/badge/ROS2-22314E?style=for-the-badge&logo=ros&logoColor=white)
![Nav2](https://img.shields.io/badge/Nav2-22314E?style=for-the-badge&logo=ros&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=for-the-badge&logo=yolo&logoColor=black)

### Backend & Web
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![JSP](https://img.shields.io/badge/JSP-007396?style=for-the-badge&logo=java&logoColor=white)

### Embedded & Hardware
![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)

### Tools & Infra
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---
## 🧩 LeetCode

[![LeetCode Stats](https://leetcard.jacoblin.cool/YOUR_LEETCODE_ID?theme=dark&font=Fira%20Code&ext=heatmap)](https://leetcode.com/devdeepdiver)

---

## 🚀 Featured Project

### 🐙 BigPinky — Multi-Robot Fleet Management System

> **4대의 TurtleBot3 + OpenManipulator-X를 단일 관제 시스템에서 운용하는 함대 관리 시스템**

재난 탐사 시나리오를 가정한 멀티로봇 관제 플랫폼. 여러 대의 로봇이 동시에 현장에 투입되어
각자의 임무(탐사, 물자 전달 등)를 우선순위에 따라 수행한다.

**🔧 Architecture**

```
┌─────────────────────────────────────────────┐
│         React + TypeScript Dashboard         │
│      실시간 로봇 상태 · 지도 · 태스크 관제      │
└────────────────────┬────────────────────────┘
                     │ WebSocket (Socket.IO)
┌────────────────────▼────────────────────────┐
│              NestJS FMS Server               │
│   Task Manager · Fleet Monitor · Planner     │
└────────────────────┬────────────────────────┘
                     │ rosbridge / domain_bridge
┌────────────────────▼────────────────────────┐
│                  ROS2 Layer                  │
│   tb3_01 ~ tb3_04 · OpenManipulator-X        │
│   Domain ID 기반 로봇 격리 (41~44 → Hub 40)   │
└──────────────────────────────────────────────┘
```

**💡 Key Engineering**
- 🗺️ **멀티로봇 위치추정** — Dynamic Obstacle Filtering & Collaborative Localization 설계
- 🔀 **Domain Bridge** — DDS Domain ID 기반 로봇 네트워크 격리 및 토픽 브리징
- 📡 **rosbridge 통신** — NestJS ↔ ROS2 WebSocket 실시간 양방향 제어
- 🎯 **Task Manager** — 우선순위 기반 작업 할당 · 배터리/상태 모니터링 · 에러 복구

---

## 🤖 More Robotics Work

| Project | Description | Stack |
|---------|-------------|-------|
| **🎮 GestDrive** | WebSocket 제스처 제어 RC카 (베어메탈 펌웨어 + AI 비전) | STM32 · ESP32 · RPi5 · YOLO · MediaPipe |
| **🦾 LeRobot ACT** | 모방학습 파이프라인 (데이터 수집 → 클라우드 학습 → 추론) | ACT Policy · RunPod · HuggingFace |
| **👁️ Visual Servoing** | YOLO + PID 기반 객체 추종 주행 시스템 | YOLO · PID · TurtleBot3 |

---



## 🌱 Currently Exploring

- 🧠 **멀티로봇 협조 위치추정** (Collaborative Localization)
- 🗺️ **동적 환경에서의 강건한 SLAM/Localization**
- 🔗 **AI 에이전트 ↔ 로봇 제어 레이어 통합**

---

<div align="center">

### 💭 *"AI의 추론을 실제 세계의 움직임으로 만드는 일을 합니다"*

![Profile Views](https://komarev.com/ghpvc/?username=kdm111&color=2E9EF7&style=flat-square&label=Profile+Views)

</div>
