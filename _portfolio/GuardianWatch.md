---
title: "2023년 K-디지털 챌린지 : NET 챌린지 캠프 시즌10"
excerpt: "다중 객체 추적 기술을 활용한 지능형 어린이집 안전 모니터링 시스템"
collection: portfolio
date: 2023-12-04
---

## 📌 프로젝트 개요

- **프로젝트명**: **GuardianWatch**
- **목표**: 어린이집 CCTV와 블루투스 데이터를 활용하여 **아이들의 행동과 위치를 모니터링**하고, 학부모가 **실시간으로 자녀의 안전을 확인**할 수 있는 시스템을 구축
- **대상 사용자**: 어린이집, 학부모, 보육 교사
- **주요 기술**:
    - 다중 객체 추적(MOT)
    - 행동 인식 AI 모델
    - BEV(Bird's Eye View) 시각화
    - 실시간 블루투스 기반 Re-ID 매핑

## 💡 문제 인식

- CCTV 열람은 법적으로 가능하지만 개인정보 문제로 실질적인 접근이 어려움
- 학부모는 자녀의 어린이집 생활을 실시간으로 확인하기 어려움
- 아동학대 및 방치 사례가 사회적 문제로 대두되고 있음

## 🛠️ 사용 기술 및 구조

### 🔧 주요 기술

- **객체 탐지 및 추적**: YOLOX + ByteTrack
- **행동 분석**: PyTorchVideo + Slow R50, Kinetics-400, AVA 데이터셋
- **Re-ID 매핑**: 블루투스 태그의 MAC 주소 & RSSI
- **시각화**: BEV 시점, 히트맵, 이동 경로, 소비 칼로리
- **네트워크**: KOREN 초고속망, HPC 서버 기반 자동 분석 시스템

<div style="display: flex; justify-content: center; gap: 40px; flex-wrap: wrap;">
  <div style="text-align: center; width: 45%">
    <img src="MOT.png">
    <p>객체 인식/행동 분석</p>
  </div>
  <div style="text-align: center; width: 45%">
    <img src="BEV.png">
    <p>Bird-Eye-View (BEV) 변환</p>
  </div>
</div>

### 🔨 시스템 구조

- CCTV → 미들 서버(RSTP 수집)
- Bluetooth 태그/워치 → 실내 유무/ID 매핑
- HPC 서버 분석 (MOT + 행동 분석 + 시각화)
- 결과 → 미들 서버 전송 → 사용자 앱으로 전달

<div align="center">
  <img src="flow.png">
</div>

## 🎯 기대 효과

- 학부모는 **실시간으로 자녀의 위치와 활동 확인** 가능
- 어린이집은 **운영 신뢰도 향상 및 관리 효율 증가**
- 개인정보 유출 없이 **시각 자료 기반 정보 전달 가능**
- 다양한 데이터 기반으로 **아동 발달 정보 파악** 가능

<div align="center">
  <img src="app_3.jpg" width="30%">
  <img src="app_5.jpg" width="30%">
  <img src="app_6.jpg" width="30%">
</div>

## 📽️ 데모 영상
<div align="center">
  <video src="https://pjs990301.github.io/portfolio/GuardianWatch/video.mp4" controls="controls" width="100%"></video>
</div>

## 🏆 수상 이력
<div align="center">
  🥈 2023년 K-디지털 챌린지:NET챌린지 시즌10 - 2023.12.04 
 <br>
  <img src="NET챌린지캠프10_은상.jpg" alt="NET챌린지캠프10_은상 수상">
</div>
