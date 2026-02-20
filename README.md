🌐 Languages: [[English](README.md)] | [한국어](README-KR.md)

# CCTV-EDR: CCTV-based Emergency Detection & Response System 
*(An emergency situation detection & reporting system leveraging existing CCTV infrastructure)*

CCTV-EDR is a system that automatically detects emergency situations using CCTV infrastructure and immediately connects detection to reporting and real-time monitoring. It uses an object detection-based AI model on CCTV footage to automatically identify situations where a person collapses, faints, or loses consciousness. After detection, it enables rapid emergency response through a real-time alert and reporting workflow designed to minimize latency. Operators can also monitor the CCTV stream where the emergency was detected in real time.

## 🏆 Awards
### Awards
- **Competition**: 2021 WINNER LINC+ Capstone Design Untact Competition
- **Period**: 2021.09 - 2021.12
- **Host**: Ministry of Education, LINC
- **Award**: 🥈 **2nd Prize**

### SW Copyright
- ©️ **No. C-2021-057286 호**

## ⚙️ Tech Stacks
- YOLOv5
- NodeJS
- Nginx
- MongoDB
- Docker

## ✨ Features
1. **Real-time object detection** on CCTV footage
2. **Real-time server notifications** for detection results
3. WebSocket-based **real-time monitoring**

## 🏗️ Architecture
<img src="https://github.com/MonoHaru/CCTV-EDR/blob/main/assets/process.png" alt="process" width="800">  
<img src="https://github.com/MonoHaru/CCTV-EDR/blob/main/assets/architecture.png" alt="architecture" width="800">

## 🎬 **Demo** 
https://github.com/user-attachments/assets/c152573d-8f20-4812-889f-2e61aaa06461

## 🔮 **Future Work** 
1. Stabilize and harden the server and database for reliable data processing
2. Improve object detection model performance and reduce false positives/false negatives

## 📜 License
The code in this repository is released under the MIT License.