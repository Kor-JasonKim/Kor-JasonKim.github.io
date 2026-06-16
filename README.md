<!-- ======================= HEADER ======================= -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1C2950,100:FF7A1A&height=190&section=header&text=Kim%20Kwon&fontSize=58&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Robot%20SW%20%C2%B7%20Embedded%20%C2%B7%20AI%20Vision&descSize=18&descAlignY=60&descColor=ffe3cc" width="100%"/>

`STM32 펌웨어` · `딥러닝 비전` · `ROS2 자율주행`

서로 다른 기술 레이어를 **하나의 안정적으로 동작하는 시스템**으로 통합하는 로봇 SW 엔지니어입니다.

</div>

---

## 👋 About Me

- 🔧 임베디드 펌웨어부터 딥러닝 비전, ROS2 자율주행까지 **레이어를 가로질러 통합하는 작업**에 강점이 있습니다.
- 🧩 모델 정확도나 알고리즘 그 자체보다, 그것이 **실제 하드웨어 위에서 끝까지 안정적으로 동작하게** 만드는 과정을 중요하게 생각합니다.
- 🔍 문제를 표면에서 덮지 않고 **원인까지 추적하는 디버깅**을 즐깁니다 — 시뮬레이션과 실환경의 노이즈 차이, OS별 버전 차이, 다중 모터 구동 시 전압 강하 같은 변수를 찾아 구조를 다시 설계합니다.

---

## 🛠 Tech Stack

**Embedded / Firmware**

![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white)
![Timer/PWM/RTC](https://img.shields.io/badge/Timer%20%C2%B7%20PWM%20%C2%B7%20RTC-1C2950?style=flat-square)
![NVIC](https://img.shields.io/badge/NVIC%20Interrupt-1C2950?style=flat-square)
![State Machine](https://img.shields.io/badge/State%20Machine-1C2950?style=flat-square)
![UART](https://img.shields.io/badge/HC--05%20UART-1C2950?style=flat-square)

**AI / Vision**

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![ResNet50](https://img.shields.io/badge/ResNet50-FF7A1A?style=flat-square)
![YOLO](https://img.shields.io/badge/YOLO-FF7A1A?style=flat-square)
![CLIP](https://img.shields.io/badge/OpenAI%20CLIP-412991?style=flat-square&logo=openai&logoColor=white)
![Grad-CAM](https://img.shields.io/badge/Grad--CAM-FF7A1A?style=flat-square)

**Robotics / Autonomous**

![ROS2](https://img.shields.io/badge/ROS2%20Jazzy-22314E?style=flat-square&logo=ros&logoColor=white)
![Nav2](https://img.shields.io/badge/Navigation2-22314E?style=flat-square)
![SLAM](https://img.shields.io/badge/SLAM-22314E?style=flat-square)
![Turtlebot3](https://img.shields.io/badge/Turtlebot3-22314E?style=flat-square)
![Gazebo](https://img.shields.io/badge/Gazebo-22314E?style=flat-square)
![Rviz](https://img.shields.io/badge/Rviz-22314E?style=flat-square)

**Web / App / Infra**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![Fusion 360](https://img.shields.io/badge/Fusion%20360%20%C2%B7%203D%20Print-FF7A1A?style=flat-square&logo=autodesk&logoColor=white)

---

## 🚀 Projects

### 🧹 AI 기반 방 청결도 분석 시스템 &nbsp;·&nbsp; [`DeepLearning_Project`](https://github.com/Kor-JasonKim/DeepLearning_Project)

> 주관적인 '깨끗함'을 정량화하는 서비스. 사진 한 장으로 청결도 점수를 매기고 **어디가 왜 지저분한지**까지 히트맵과 자연어로 짚어줍니다. 분류·객체 탐지·이미지-텍스트 세 모델을 병렬 실행해 가중합한 종합 지수를 산출하고, 사용자끼리 서로의 점수를 매겨 AI 판단과 비교하는 커뮤니티로 확장했습니다.

| 지표 | 방 모델 | 책상 모델 |
|---|:---:|:---:|
| Accuracy | **0.9597** | **0.9656** |
| Binary F1 | **0.9559** | **0.9560** |
| AUC | 0.992 | 0.997 |

`TensorFlow` `ResNet50` `YOLO` `CLIP` `Grad-CAM` `Flask` `MySQL` `Raspberry Pi`

<br>

### 💊 STM32 스마트 알약 자동 디스펜서 &nbsp;·&nbsp; [`STM_Project`](https://github.com/Kor-JasonKim/STM_Project)

> 복약 시간과 요일을 앱에서 설정하면, 정해진 시각에 해당 요일의 약이 자동 배출되는 디스펜서. 약통 회전·배출·초음파 기반 복용 확인까지 **하나의 상태 머신**으로 제어하고, 기구 모델링과 3D 프린팅, 앱 시제품까지 직접 진행해 완결된 기기로 완성했습니다.

```text
IDLE → FORWARD → WAIT → BACKWARD → FINISHED      # 상태 머신 기반 제어
정밀 위치 제어 : 32 step × 64 × 7.8 ÷ 7 days ≈ 2,282 steps
```

`STM32 / C` `Timer·PWM·RTC` `NVIC` `HC-05` `스텝·서보·DC 모터` `초음파` `MIT App Inventor`

<br>

### 🤖 음성 인식 기반 장애물 회피 주행 &nbsp;<sub>· 졸업 종합설계 우수상</sub>

> 시야가 막힌 코너 너머의 위험을 **소리로 먼저 읽는** 자율주행 접근. 직접 설계한 경량 음원 인식 모델로 장애물 방향을 추정해, 충돌 전에 우회 경로를 미리 계획합니다. *(Latency 1.086ms · 2.4M params, Conformer 대비 약 6× 경량)*

`ROS2` `Nav2` `Turtlebot3` `PyTorch` `OpenCV` `SLAM`

<br>

### 🚨 재난 현장 자율주행 구호 로봇 &nbsp;<sub>· 진행 중</sub>

> 사람이 들어가기 어려운 재난 환경을 로봇이 스스로 탐사. 조종 없이 미지의 지형을 주행하며 **지도를 작성하고 조난자 위치를 파악하는** 자율 탐사 기능을 담당하고 있습니다.

`ROS2 Jazzy` `VicPinky` `OMX` `SLAM` `Nav2` `STM32` `Raspberry Pi`

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Kor-JasonKim&show_icons=true&hide_border=true&title_color=FF7A1A&icon_color=FF7A1A&text_color=141D33&bg_color=FBFCFE" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Kor-JasonKim&layout=compact&hide_border=true&title_color=FF7A1A&text_color=141D33&bg_color=FBFCFE" height="165"/>

</div>

---

## 📫 Contact

[![Email](https://img.shields.io/badge/drpyke0320@gmail.com-FF7A1A?style=flat-square&logo=gmail&logoColor=white)](mailto:drpyke0320@gmail.com)
[![GitHub](https://img.shields.io/badge/Kor--JasonKim-141D33?style=flat-square&logo=github&logoColor=white)](https://github.com/Kor-JasonKim)

<div align="center">
<sub>경희대학교 전자공학부 · AI 융합 로봇 SW 개발자 · TOEIC 925 · HSK 5급</sub>
</div>
