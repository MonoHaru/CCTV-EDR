🌐 Languages: [[English](README.md)] | [[한국어](README-KR.md)]

# CCTV-EDR: CCTV-based Emergency Detection & Response System 
*(CCTV 인프라를 활용한 비상 상황 탐지 및 신고 시스템)*

CCTV-EDR은 CCTV 인프라를 활용해 비상 상황을 자동으로 탐지하고, 즉시 신고 및 모니터링까지 연결하는 시스템입니다. CCTV 영상에서 객체 탐지 기반 AI 모델을 활용하여 사람이 쓰러지거나 실신(의식 소실)하는 상황을 자동으로 감지합니다. 탐지 이후에는 지연 시간을 최소화하도록 설계된 실시간 알림 및 신고 흐름을 통해 응급 대응이 가능하며, 관제자는 비상 상황이 포착된 CCTV 영상을 실시간으로 확인할 수 있습니다.

## 🏆 Awards
### 수상
- **대회명**: 2021 WINNER LINC+ 캡스톤디자인 언택트 경진대회
- **기간**: 2021.09 - 2021.12
- **주최**: 교육부, LINC
- **수상**: 🥈 **2등상**

### SW 저작권
- ©️ **제 C-2021-057286 호**

## ⚙️ Tech Stacks
- YOLOv5
- NodeJS
- Nginx
- MongoDB
- Docker

## ✨ Features
1. CCTV 영상 기반 **실시간 객체 탐지**
2. 탐지 결과에 대한 **실시간 서버 알림**
3. WebSocket 기반 **실시간 모니터링**

## 🏗️ Architecture
<img src="https://github.com/MonoHaru/CCTV-EDR/blob/main/assets/process-kr.png" alt="process" width="800">  
<img src="https://github.com/MonoHaru/CCTV-EDR/blob/main/assets/architecture.png" alt="architecture" width="800">

## 🎬 **Demo** 
https://github.com/user-attachments/assets/c152573d-8f20-4812-889f-2e61aaa06461

## 🔮 **Future Work** 
1. 데이터 처리를 위한 서버 및 데이터베이스 안정화(견고화)
2. 객체 탐지 모델 성능 개선 및 오탐/미탐 감소

## 📜 License
The code in this repository is released under the MIT License.