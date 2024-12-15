# 😀 Face World: 사용자 얼굴 특징 분석 및 추천 서비스

### 📅 개발기간
- 2024.03.29 ~ 2024.05.09

### ⚙️ 기술스택
- **AI**: Tensorflow
- **Front-end**: HTML, CSS, JavaScript
- **Back-end**: Flask
- **Database**: MySQL
<details>
<summary>🌳 버전</summary>
  
- Python 3.9.18
- Flask 3.0.2
- tensorflow 2.16.1
- keras 3.1.1
  
</details>

### 👨‍💼 담당 작업(구동빈)

- **Inception v3**모델 **파인튜닝**(연예인, 동물), 파인튜닝에 필요한 **이미지 데이터 전처리**
- **Flask 소스코드 작성** 및 Web 연동
- HTML, CSS, JavaScript을 활용한 **웹 구현** (메인, 로그인, 업로드, 결과)
- 얼굴 분석 결과에 맞는 **동영상 추천** 기능 구현

<details>
<summary>👨‍💼 팀소개</summary>
  
- 👨‍💼구동빈
  - 기획 | Flask | 프론트엔드 | 데이터 전처리 | AI 모델링 | Apache, Flask 연동 
- 👨‍💼김현종
  - 데이터 수집 | AI 모델링
- 👨‍💼박종관
  - Flask | 프론트엔드 | 데이터 전처리 | AI 모델링
</details>

## 1. 개요
- 사용자의 **얼굴 특징**을 **AI로 분석**하여 얼굴 특징과 유사한 것들을 찾아주는 서비스
- 사용자는 자신의 사진을 업로드하고 다양한 분석 결과를 확인하며 재미를 얻을 수 있음

## 2. 화면 구성
### ■ 로그인 페이지
<img src="https://github.com/Knell999/ai_service_project/assets/106071689/e9120ee0-7144-4315-bf4e-6e2179f048fb" width="50%" height="50%"/>

- 로그인 시 데이터베이스의 정보 조회 후 로그인 기능 구현

### ■ 메인 페이지
<img src="https://github.com/Knell999/ai_service_project/assets/106071689/1f5a25f7-6e04-40a5-b4b5-2102866475ad" width="50%" height="50%"/>

- 로그인 시 사용자 이름 표시 기능 구현
- 네 가지 이미지 분석 기능 구현

### ■ 업로드 페이지
<img src="https://github.com/Knell999/ai_service_project/assets/106071689/bb4cfedc-e863-4a6b-9f03-41b3e99237f7" width="50%" height="50%"/>

- 이미지 업로드 시 이미지 데이터 전처리 자동화 기능 구현
- 전처리된 이미지를 파인튜닝한 Inception v3 모델로 분류 및 유사도 도출 기능 구현

### ■ 결과 페이지
<img src="https://github.com/Knell999/ai_service_project/assets/106071689/12b74358-a5c1-4bce-8033-5d5d01abf217" width="50%" height="50%"/>

- AI 모델 결과에 따라 키워드를 추출하여 관련 유튜브 동영상 추천 기능 구현

### ■ 마이 페이지
<img src="https://github.com/Knell999/ai_service_project/assets/106071689/5cadf41d-0173-461e-9ad9-96c5aec1425a" width="50%" height="50%"/>

- 이용했던 기능 별로 이용 내역 조회 기능 구현

### ■ History 페이지
<img src="https://github.com/Knell999/ai_service_project/assets/106071689/8d6a16d5-7791-4ce9-ab44-9675a2c96d21" width="50%" height="50%"/>

 - 사용자별 이용 기록을 데이터베이스에서 조회해 표시 및 삭제 기능 구현
