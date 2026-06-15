<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=200&section=header&text=Hello%2C%20I'm%20Junsu%20🤖&fontSize=45&fontColor=ffffff&fontAlignY=38&desc=Robotics%20Software%20Engineer%20%7C%20System%20Integration&descAlignY=58&descSize=18" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Nunito&weight=700&size=20&duration=3000&pause=1000&color=FF8C61&center=true&vCenter=true&width=620&lines=🤖+로봇에게+생각하는+법을+가르칩니다;🔗+AI+출력을+실제+행동으로+연결합니다;🌍+현장에서+동작하는+로봇을+만듭니다;💡+Perception+→+Planning+→+Action)](https://git.io/typing-svg)

</div>

---

<div align="center">

```
   ( •_•)        (•_• )
   ／|            |＼
  Robotics    Integration
  Engineer     Engineer
     └────────────┘
       같은 사람입니다
```

</div>

---

## 🌿 About Me

```python
class Junsu:
    def __init__(self):
        self.role     = "Robotics System Integration Engineer"
        self.mission  = "AI 출력 → 로봇 행동 → 실제 서비스"
        self.location = "South Korea 🇰🇷"
        self.special  = ["끝장 볼때까지 열심히 해보기"]

    def strengths(self):
        return {
            "🧠 AI":        "YOLO · ACT Policy · MediaPipe",
            "🤖 Robotics":  "ROS2 · Nav2 · SLAM · TF",
            "🔌 Embedded":  "STM32 · ESP32 · RPi · UART · PWM",
            "🌐 Backend":   "NestJS · FastAPI · Spring · rosbridge",
            "🎨 Frontend":  "React · TypeScript · Socket.IO",
        }

    def philosophy(self):
        return "로봇이 실제 현장에서 동작하려면, 끝까지 연결되어야 한다"
```

---

## 🛠️ Tech Stack

### 🤖 Robotics & AI
![ROS2](https://img.shields.io/badge/ROS2-22314E?style=for-the-badge&logo=ros&logoColor=white)
![Nav2](https://img.shields.io/badge/Nav2-22314E?style=for-the-badge&logo=ros&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=for-the-badge&logo=yolo&logoColor=black)

### 🌐 Backend & Web
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![JSP](https://img.shields.io/badge/JSP-007396?style=for-the-badge&logo=java&logoColor=white)

### 🔌 Embedded & Hardware
![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)

### 🗄️ Database
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### ⚙️ Tools & Infra
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## 🐙 Featured Project — BigPinky

> **재난 탐사 시나리오 기반 멀티로봇 함대 관제 시스템**
> TurtleBot3 × 4대 + OpenManipulator-X를 단일 대시보드에서 운용

```
┌──────────────────────────────────────────────┐
│        React + TypeScript Dashboard           │
│    실시간 로봇 상태 · 지도 · 태스크 관제 🗺️     │
└───────────────────┬──────────────────────────┘
                    │ WebSocket (Socket.IO)
┌───────────────────▼──────────────────────────┐
│             NestJS FMS Server                 │
│  Task Manager · Fleet Monitor · Route Planner │
└───────────────────┬──────────────────────────┘
                    │ rosbridge / domain_bridge
┌───────────────────▼──────────────────────────┐
│               ROS2 Layer (Hub 40)             │
│  tb3_01~04 · OpenManipulator-X               │
│  Domain ID 기반 로봇 격리 (41~44 → 40)        │
└──────────────────────────────────────────────┘
```

💡 **Key Engineering Points**
- 🗺️ Dynamic Obstacle Filtering & Collaborative Localization
- 🔀 DDS Domain ID 기반 멀티로봇 네트워크 격리
- 📡 rosbridge WebSocket 실시간 양방향 제어
- 🎯 우선순위 기반 태스크 매니저 & 에러 복구

---

## 🤖 More Projects

| 🏷️ | Project | Description | Stack |
|----|---------|-------------|-------|
| 🎮 | **GestDrive** | 제스처 제어 RC카 (베어메탈 펌웨어 + AI 비전) | STM32 · ESP32 · RPi5 · YOLO |
| 🦾 | **LeRobot ACT** | 모방학습 파이프라인 (수집 → 훈련 → 추론) | ACT Policy · RunPod · HuggingFace |
| 👁️ | **Visual Servoing** | YOLO + PID 객체 추종 자율주행 | YOLO · PID · TurtleBot3 |
| 🏭 | **Smart Factory** | PLC 모니터링 + 자연어 명령 파싱 | Modbus TCP · Streamlit |
| 🎯 | **GCC** | MediaPipe + KNN 제스처 인식 OS/RC 제어 | MediaPipe · KNN · Python |

---

## 🧩 LeetCode

<div align="center">

[![LeetCode](https://img.shields.io/badge/LeetCode-629%20solved-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/u/devdeepdiver)

[![LeetCode Stats](https://leetcard.jacoblin.cool/devdeepdiver?theme=dark&font=Nunito&ext=heatmap)](https://leetcode.com/u/devdeepdiver)

</div>

---

## 🌱 Currently Exploring

- 🧠 **멀티로봇 협조 위치추정** (Collaborative Localization)
- 🗺️ **동적 환경에서의 강건한 AMCL / SLAM**
- 🔗 **AI 에이전트 ↔ 로봇 제어 레이어 통합**
- 📋 **FMS 태스크 매니저 설계 & 구현**

---

<div align="center">

### 🌟 *"로봇이 실제 현장에서 동작하려면, AI · 하드웨어 · 서비스가 끊김 없이 연결되어야 합니다"*
### *그 연결 지점을 설계하고 구현합니다* 🤖

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=kdm111&color=FF8C61&style=for-the-badge&label=VISITORS)

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=120&section=footer" />

</div>
