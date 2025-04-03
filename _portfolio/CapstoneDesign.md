---
title: "캡스톤 디자인"
excerpt: "Wi-Fi Sensing과 AI 스피커 기술을 활용하여 독거노인의 건강과 안전을 모니터링하고 긴급신고까지 가능한 솔루션을 개발하는 프로젝트"
collection: portfolio
date: 2023-06-16
---
## 📌 프로젝트 개요
- **프로젝트명**: **MoWA**(**Mo**nitoring the elder with **W**i-Fi and **A**I speaker) 
- **목표**: Wi-Fi Sensing과 AI 스피커 기술을 활용하여 **독거노인의 건강과 안전을 실시간 모니터링**하고, **긴급 상황에 자동 신고**가 가능한 스마트 케어 솔루션 개발  
- **사용 대상**: 혼자 거주하는 고령자 (독거노인)  


## 💡 문제 인식
- 고령화 사회 진입과 함께 독거노인 증가
- 기존의 돌봄 서비스는 한계가 있으며, 24시간 비접촉 모니터링 시스템 필요


## 🛠️ 주요 기능 및 기술 스택

### 🎯 제공 서비스
- Wi-Fi Sensing 기반 실시간 활동 감지
- AI 스피커를 통한 음성 상호작용 및 긴급 신고
- 모바일 앱을 통한 월간 활동 기록 확인

### ⚙️ 사용 기술
- **Wi-Fi Sensing**
  - Raspberry Pi 4 + Nexmon CSI: CSI 데이터 수집
  - TensorFlow, PyTorch: Supervised Learning / Meta Learning 기반 모델 구현
- **백엔드**
  - Django + MySQL: API 서버 및 데이터 관리
- **모바일 앱**
  - Kotlin (Android): 사용자용 앱 개발
- **AI 스피커**
  - Node.js, Firebase, Dialogflow: 음성 인터페이스 및 커스텀 명령 설계
- **디자인 협업**
  - Figma: UI/UX 설계 및 팀 협업


## 🙋 담당 역할

### ✅ Wi-Fi Sensing
- Raspberry Pi + Nexmon으로 CSI 데이터 수집 자동화
- Supervised Learning 기반 행동 분류 모델 개발  
- 환경 변화에 유연한 Meta Learning (Few-shot Learning) 모델 적용

### ✅ Django 백엔드
- Android 앱과 연동되는 RESTful API 21종 개발
- Model 기반 구조 설계 및 Swagger로 API 문서화
- MySQL 데이터베이스 연동 및 관리


## 🔗 링크
- GitHub: [https://github.com/GachonMoWA](https://github.com/GachonMoWA)  
- 시연 영상: [https://www.youtube.com/watch?v=tfXx67bdHSE](https://www.youtube.com/watch?v=tfXx67bdHSE)
<iframe src="https://www.youtube.com/embed/tfXx67bdHSE" frameborder="0" allowfullscreen></iframe>
