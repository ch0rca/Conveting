# 🐶 ConVeting

> AI 기반 반려견 비대면 건강 관리 서비스

ConVeting은 반려견 보호자가 시간과 장소의 제약 없이 반려견의 건강 상태를 관리할 수 있도록 지원하는 헬스케어 플랫폼

AI 질환 진단, 비대면 수의사 상담, 커뮤니티, 일정 관리 기능을 통합하여 반려견의 건강 관리를 더욱 쉽고 편리하게 제공합니다.

---

## 📌 Project Overview

반려동물 시장의 성장과 함께 보호자들의 의료비 부담, 병원 방문의 시간적·공간적 제약 문제가 증가하고 있습니다.

ConVeting은 이러한 문제를 해결하기 위해 AI 기반 질환 진단과 비대면 수의사 상담 서비스를 제공하며, 반려견 건강 관리의 접근성을 높이는 것을 목표로 개발되었습니다.

### 개발 기간

* 2024.07.01 ~ 2024.08.21

---

## ✨ Main Features

### 🤖 AI 질환 진단

* 반려견 피부 질환 6종 진단
* 반려견 안구 질환 10종 진단
* 사진 업로드 기반 AI 분석
* 질환별 발생 확률 제공

### 👨‍⚕️ 비대면 수의사 상담

* 수의사 예약 기능
* Zoom API 기반 화상 상담
* 실시간 채팅 상담

### 📝 커뮤니티

* 게시글 작성 및 조회
* 댓글 기능
* 질환 정보 공유

### 📅 마이페이지

* 반려견 정보 관리
* AI 진단 이력 조회
* 상담 내역 관리
* 캘린더 기반 일정 관리

---

## 🛠 Tech Stack

### Frontend

* React
* React Native
* JavaScript
* JSX
* CSS

### Backend

* Spring Boot
* Spring Security
* Spring Data JPA
* Django
* Django REST Framework

### AI

* Python
* TensorFlow
* Keras
* CNN

### Database

* MySQL

### Tools

* IntelliJ IDEA
* VS Code
* Jupyter Notebook
* Google Colab

---

## 🧠 AI Model

### 피부 질환 진단

* AI Hub 반려동물 피부 질환 데이터 활용
* CNN 기반 이진 분류 모델
* 평균 Accuracy: **0.76**
* 평균 AUC-ROC: **0.84**

### 안구 질환 진단

* AI Hub 반려동물 안구 질환 데이터 활용
* CNN 기반 분류 모델
* 평균 Accuracy: **0.90**
* 평균 AUC-ROC: **0.94**

---

## 🏗 Architecture

```text
Client (React / React Native)
        │
        ▼
Spring Boot API Server
        │
 ┌──────┴──────┐
 ▼             ▼
MySQL      Django AI Server
                │
                ▼
          CNN Models
```

---

## 📱 주요 화면

* 로그인 / 회원가입
<img width="995" height="559" alt="image" src="https://github.com/user-attachments/assets/18d08a7f-4aba-4d1c-a9f8-1656ede33f10" />
* 메인 홈
* AI 건강 진단 & 결과 조회
<img width="995" height="558" alt="image" src="https://github.com/user-attachments/assets/7931fe91-b623-4d5f-af84-6edf664ad899" />
* 비대면 수의사 상담
<img width="995" height="553" alt="image" src="https://github.com/user-attachments/assets/05575f08-d050-4194-85f2-a28249d1f741" />
* 커뮤니티
<img width="995" height="558" alt="image" src="https://github.com/user-attachments/assets/51295da9-f02d-4d22-9e49-3f1a065fdf79" />
* 마이페이지
<img width="995" height="556" alt="image" src="https://github.com/user-attachments/assets/68cf3db1-6e08-4a25-9bfd-21e4fd61fd01" />
* 일정 관리 캘린더

---

## 🚀 Expected Benefits

* 병원 방문 전 간단한 건강 상태 확인
* 의료비 부담 감소
* 반려견 건강 관리 편의성 향상
* 신뢰성 있는 전문가 상담 제공
* 반려동물 헬스케어 시장 확장 가능성

---

## 🔗 Repository

https://github.com/ConVeting
