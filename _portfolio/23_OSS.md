---
title: "2023년 공개SW 개발자대회"
excerpt: "카메라와 웨어러블 기반의 기존 모니터링 시스템의 한계를 극복하고, Wi-Fi Sensing을 활용한 차세대 독거노인 케어 서비스"
collection: portfolio
date: 2023-12-01
---

## 📌 프로젝트 개요

- **프로젝트명**: **MoWA**(**Mo**nitoring the elder with **W**i-Fi and **A**I)
- **프로젝트 소개**: 카메라와 웨어러블 기반의 기존 모니터링 시스템의 한계를 극복하고, Wi-Fi Sensing을 활용한 **차세대 독거노인 케어 서비스**를 제공
- **사용 대상**: 혼자 사는 노인들(독거노인)


## 💡 문제 인식

- 고령화 사회로 인한 독거노인 수 증가
- 기존 스마트 케어 서비스의 사생활 침해, 기기 착용 불편 등의 문제
- 독거노인의 상태를 상시 파악할 수 있는 비접촉 서비스 부족


## 🛠️ 주요 기능 및 기술 스택

### 🎯 제공 서비스

- Wi-Fi Sensing 기반 독거노인 상태 모니터링
- 웹 대시보드를 통한 관리자용 모니터링 기능
- 안드로이드 앱을 통한 월간 활동 기록 조회
- **CSI 데이터 수집 도구 오픈소스 제공**

### ⚙️ 사용 기술

- **하드웨어 및 데이터 수집**
    - Raspberry Pi 4, Nexmon CSI
- **AI 모델링**
    - PyTorch 기반 Wi-Fi Sensing 모델 구현
- **서버 및 대시보드**
    - Flask, Dash, MySQL
- **모바일 앱**
    - Kotlin, Android
    - Kakao Map API 활용
- **디자인**
    - Figma 기반 UI/UX 디자인 협업


## 🙋 담당 역할

### ✅ Wi-Fi Sensing

- Raspberry Pi + Nexmon CSI를 활용하여 **CSI 데이터 수집 자동화**
- 환경 변화에 영향을 받는 Wi-Fi Sensing 특성을 해결하기 위해 **Few-shot Learning(Meta Learning)** 기반 모델 개발

### ✅ Flask 백엔드 & Dash

- Android 앱 연동용 REST API **총 27종 설계 및 개발**
- Swagger로 API 테스트 문서화
- MySQL을 이용한 데이터 저장 및 관리
- Dash 프레임워크를 활용한 관리자 대시보드 및 시각화 페이지 구현

### ✅ Wi-Fi Sensing 라벨링 도구 개발

- CSI 수집 시 **패턴 시각화 및 라벨링이 어려운 문제**를 해결하기 위해
- 실시간 CSI 시각화 및 저장 가능한 **오픈소스 수집 도구 개발**
- 데이터 수집 정확도 및 효율성 개선

<div align="center">
  <video src="https://github.com/oss-inc/mowa-wifi-sensing-labelling/assets/70201882/b2ab5211-743e-47a0-adb7-20b0a41a3d7c" controls="controls" width="100%">
  </video>
  <br>📽️ 시연 영상
</div>

## 🏆 수상 이력

<div align="center">
  🥉 2023년 공개SW 개발자대회 동상 (후원기업상) - 2023.12.01 
 <br>
  <img src="2023_공개SW개발자대회_동상.jpg" alt="2023년 공개SW 개발자대회 동상 수상">
</div>


## 🔗 링크

- GitHub: [https://github.com/oss-inc](https://github.com/oss-inc)