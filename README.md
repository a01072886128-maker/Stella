# TOKKI TALK – 여자어 번역기

## 1. 프로젝트명 TOKKI TALK 
– 남자들에게 어려운 여자들의 이중언어 속 메시지를 분석, 번역해주는 서비스를 제공하며
  상황별 맞춤 대응 전략을 제안하는 번역 서비스
<br>

<img width="1920" height="1080" alt="제목을 입력하세요 1" src="https://github.com/user-attachments/assets/83052b9c-b161-494d-a1cc-4fcc0925178e" />

---

## 2. 서비스 소개
연인간 짧은 카카오톡/메신저 메시지에서 한국어 속에 숨은 진짜 의미를 분석,번역해주고 적절한 대응 문장을 제안해주는 한국어 번역 서비스입니다.  

<img width="1920" height="1080" alt="제목을 입력하세요 3" src="https://github.com/user-attachments/assets/8e83082d-4c8e-4f12-a9eb-c30fe078636d" />

<img width="1920" height="1080" alt="제목을 입력하세요 4" src="https://github.com/user-attachments/assets/ced689bf-517e-4728-8200-2909ca7f3571" />
<img width="1920" height="1080" alt="제목을 입력하세요 5" src="https://github.com/user-attachments/assets/dc975397-688b-4ce8-90b3-1be273e1d093" />

---

## 3. :calendar:프로젝트 기간
2025년 7.18 ~ 8.22 (약 2주)

---

## 4. 주요 기능

- **여자어 번역 서비스 💬**  
  - 일상적인 대화 속에서 사용되는 **여자들의 이중 언어**를 분석합니다.  
  - 예: “괜찮아”라는 표현이 실제로는 ‘정말 괜찮음’인지, ‘섭섭함이 숨겨져 있음’인지를 감정 레벨 기반으로 판별합니다.  
  - 분석 결과에 따라 **최대 3~4개의 대응 문장**을 랜덤 추천하여, 상황에 맞는 답변을 제시합니다.  

- **센스고사 기능 🎯**  
  - 사용자에게 상황별 문제(퀴즈)를 제시하여, **자신의 ‘센스 지수’**를 확인할 수 있게 합니다.  
  - 단순한 번역 서비스 이용을 넘어, **게임적 요소**를 통해 사용자가 서비스에 자연스럽게 참여하도록 유도합니다.  
  - 채점 결과와 피드백을 제공하여, 사용자가 반복적으로 학습/체험할 수 있습니다.  

- **사용자 맞춤형 반응 제안 🤝**  
  - 입력 문장의 감정 분석 결과와 선톡여부, 시간, 답장시간등 이모티콘, ㅋㅋ,ㅎㅎ 까지 감정화하여 **맞춤형 대응 방안**을 제시합니다.  
  - 사용자는 자신의 대화 패턴과 반응을 기록/조회할 수 있으며, 점차적으로 더 나은 커뮤니케이션 방식을 학습할 수 있습니다.  

---

## 5. 기술 스택

<img width="1920" height="1080" alt="제목을 입력하세요 13" src="https://github.com/user-attachments/assets/c6ebb94f-f8d8-4a84-a9e7-a32f24e62c0d" />

## 🔧 기술 스택

**언어**  
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**프레임워크**  
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)

**DB & 데이터**  
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![CSV](https://img.shields.io/badge/CSV-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

**서버 & 빌드 툴**  
![Apache Tomcat](https://img.shields.io/badge/Tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=black)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)

**ORM & 데이터 매퍼**  
![MyBatis](https://img.shields.io/badge/MyBatis-000000?style=for-the-badge&logo=databricks&logoColor=white)

**API**  
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)

**협업 툴**  
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)

---

## 6. 시스템 아키텍처

본 프로젝트의 전체 구조는 **Front-End, Back-End, Database, AI API**로 나눌 수 있습니다. 
<img width="1920" height="1080" alt="제목을 입력하세요 16" src="https://github.com/user-attachments/assets/3eba0507-c2fd-470a-b7d8-244644facb4e" />

<img width="1920" height="1080" alt="제목을 입력하세요 14" src="https://github.com/user-attachments/assets/d21d0951-14c0-406b-a342-eb33f6c6d28d" />

- **Front-End**: HTML, CSS, JavaScript 기반 화면 구성  
- **Back-End**: JSP & Servlet, Tomcat, Maven, CSV 데이터 처리  
- **Database 연동**: Oracle DB, MyBatis를 활용한 데이터 관리  
- **AI 분석**: OpenAI GPT-4o API를 통한 감정 분석 및 대응 문장 생성  

---

## 7. 서비스 흐름도

사용자 서비스는는 **회원가입/로그인 → 메인화면 → 기능 선택 → 결과/히스토리 관리**의 흐름으로 구성됩니다.

<img width="1920" height="1080" alt="제목을 입력하세요 11" src="https://github.com/user-attachments/assets/a8334b12-26d9-4ed3-82f9-eb770a86a85e" />

### 1) 진입 & 인증
- `회원가입` → 기본 정보 등록
- `로그인` → 세션 생성 후 메인화면 이동

### 2) 메인화면 (허브)
- 제공 메뉴: `소개하기`, `대화하기`, `센스고사`, `마이페이지`

### 3) 핵심 기능
- **소개하기**
  - 서비스 목적/사용법 안내

- **대화하기**
  - 텍스트 입력(필수), 이미지 첨부(옵션)
  - 분석 요청 →  여자어 특화 GPT-4o 호출 → 의미/감정 해석 + 대응 문장 제안
  - 결과를 **나의 히스토리**에 저장

- **센스고사**
  - 상황별 문항 제공 → 사용자의 선택 수집
  - 피드백/점수 제공(센스 지수)

- **마이페이지**
  - `나의 히스토리 조회` (과거 분석 결과 목록/상세)
  - `회원정보 수정` (닉네임, 연락처 등)

### 4) 데이터 흐름 요약
- 입력(텍스트/이미지) → 분석 요청 전송 → 모델 응답 수신 → 결과 렌더링 → 히스토리 저장/조회

---
## 8. ER-Diagram

<img width="1265" height="996" alt="image" src="https://github.com/user-attachments/assets/3284239c-6fd4-4f6e-a791-9fcfc9727496" />

---
## 9. 화면 구성

<img width="1920" height="1080" alt="제목을 입력하세요 17" src="https://github.com/user-attachments/assets/be822d9c-98e6-4d92-a7cd-431587b570b4" />

<img width="1920" height="1080" alt="제목을 입력하세요 18" src="https://github.com/user-attachments/assets/f84adda6-711b-46fe-8c28-d0501f06651a" />

<img width="1920" height="1080" alt="제목을 입력하세요 19" src="https://github.com/user-attachments/assets/df8b4cf3-3f48-48c2-b172-a09c65fe4e59" />

<img width="1920" height="1080" alt="제목을 입력하세요 20" src="https://github.com/user-attachments/assets/5b6d0cd5-665c-40dc-9ef2-ad84ff6dfe1c" />

<img width="1920" height="1080" alt="제목을 입력하세요 21" src="https://github.com/user-attachments/assets/d3ff1e2a-f4d4-4a9d-9728-652ccf18ff26" />

<img width="1920" height="1080" alt="제목을 입력하세요 22" src="https://github.com/user-attachments/assets/548af3af-588a-4925-8275-ea415179f9d1" />

---
## 10. 시연영상

https://github-production-user-asset-6210df.s3.amazonaws.com/224683260/483044320-ea1d59ca-85c7-47c0-aeb1-d77b98917170.mp4?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20250921%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20250921T040142Z&X-Amz-Expires=300&X-Amz-Signature=9a372d30f9cba9351b3070e624318812fb56e2add5b2b7aa2df44b59e567cf23&X-Amz-SignedHeaders=host

---
## 11. 기대효과 및 활용방안

<img width="1920" height="1080" alt="제목을 입력하세요 26" src="https://github.com/user-attachments/assets/c211a983-d030-4e2a-9a23-18fcc934bbb9" />

<img width="1920" height="1080" alt="제목을 입력하세요 27" src="https://github.com/user-attachments/assets/d79395e7-ca35-43cc-afd5-bde05485c4d0" />

