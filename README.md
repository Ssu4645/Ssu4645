# 김동우

**ROS 2 · Robotics · Python**

로봇의 개별 기능을 구현하는 것뿐 아니라,  
**인지 · 행동 제어 · 자율주행 · 데이터 기록 · 웹 서비스**를 하나의 흐름으로 연결하는 과정에 관심이 있습니다.

현재 ROS 2 기반 로봇 프로젝트를 중심으로 자율주행과 로봇 소프트웨어를 개발하고 있습니다.

## Main Projects

### [ODI · 호기심 많은 반려 탐험 로봇](https://github.com/ros2-team/ProjectOdi)

ROS 2 기반으로 **자율 탐험 → 객체 발견 → 호기심 판단 → 관찰 → 기억 → 일기 생성**을 연결한 실내 탐험 로봇입니다.

- Mission Manager · Behavior Executor 기반 행동 흐름 설계
- Nav2 · Cartographer 기반 자율 탐험
- YOLOv8 객체 인지 및 관찰 연계
- MySQL 기반 관찰 기록 저장·조회
- OpenAI API 기반 특징 분석 및 탐험 일기 생성
- Flask 기반 웹 UI와 ROS 2 시스템 통합

### [Aero · 자율주행 공항 안내 로봇](https://github.com/ros2-team/Project_Aero)

사용자가 목적지를 선택하면 로봇이 실내에서 자율주행으로 안내하고, QR 호출과 웹 화면을 통해 서비스 흐름을 연결한 공항 안내 로봇입니다.

- Nav2 · AMCL 기반 실내 자율주행
- Behavior Tree · Blackboard 기반 행동 제어
- YOLOv8 · OpenCV 기반 사용자 인지
- Flask · MySQL 기반 안내 서비스
- 웹과 ROS 2 간 명령·상태 연동

## Tech Stack

**Robotics**  
ROS 2 Humble · Nav2 · Cartographer · AMCL · TurtleBot3

**Programming**  
Python · C++ · Java

**Vision & AI**  
YOLOv8 · OpenCV · OpenAI API

**Backend & Data**  
Flask · MySQL

**Environment & Tools**  
Ubuntu · Git · GitHub · VS Code

---

대표 프로젝트는 아래 Pinned repositories에서 바로 확인할 수 있습니다.
