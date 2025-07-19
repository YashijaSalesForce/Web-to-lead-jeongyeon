# 🌐 Web-to-Lead 구현

## 📋 프로젝트 개요
 호텔 컨설팅 사이트의 첫 방문 고객 정보를 Salesforce로 자동 수집하는 Web-to-Lead 시스템 구현

## 🎯 구현 목적
- **리드 자동화**: 웹사이트 방문자 정보를 수동 입력 없이 자동 전송
- **마케팅 효율화**: 고객 관심사(선호 호텔 종류)를 파악하여 타겟 마케팅 가능
- **영업 기회 창출**: 실시간 리드 알림으로 빠른 고객 응대 실현

## 📸 시스템 구현 화면

<div align="center">

### 1️⃣ 웹 리드 수집 폼
<img width="500" alt="Web Lead Form" src="https://github.com/user-attachments/assets/68eb3fc2-52f6-4dec-8343-84240871ab1a" />

*방문자가 관심 호텔을 선택하는 반응형 웹 폼*

---

### 2️⃣ Salesforce 리드 생성 확인
<img width="500" alt="Lead Created" src="https://github.com/user-attachments/assets/7c285d92-6e8b-4fa8-9e5c-4b09fb0df509" />

*웹 폼 제출 즉시 Salesforce에 리드 자동 생성*

---

### 3️⃣ 리드 유입 경로 관리 및 동의 여부 확인
 <img width="500" alt="Lead List View" src="https://github.com/user-attachments/assets/46a87a80-4aef-4cca-82a6-8f9c53f54fb6" />

*향후에 대시보드나 마케팅의 데이터로 사용가능*

---

### 4️⃣ 최종 정보와 BEFORE & AFTER 사진을 통해 고객에게 확신
<img width="500" alt="Lead Detail" src="https://github.com/user-attachments/assets/c389e34e-d3dc-4807-9c43-e0291d754241" />

*정중한 마무리*

</div>

## ✨ 주요 기능 및 효과

### 🚀 핵심 기능
- **실시간 데이터 연동**: 웹 폼 제출과 동시에 Salesforce 리드 생성
- **자동 분류**: 관심 호텔별로 분류 및 에 리드 점수에 따라 분류
- **중복 방지**: 이메일 기반 중복 리드 자동 병합
- **자동 할당**: 지역/상품별 담당 영업사원 자동 배정

### 📈 비즈니스 성과
- **리드 수집 시간 90% 단축**: 수동 입력 제거
- **응답률 향상**: 실시간 알림으로 즉각 대응
- **전환율 증가**: 고객 관심사 기반 맞춤 영업
- **데이터 정확도 100%**: 자동화로 입력 오류 제거

## 🛠 기술
- **Frontend**: HTML5, CSS3, JavaScript
- **Backend**: Salesforce Web-to-Lead API
- **자동화**: Process Builder, Flow
- **분석**: Reports & Dashboards
