# TokkiTalk – 여자어 번역기

## 1. 프로젝트명 (팀명: SU:DIVE)
TokkiTalk – 남자들에게 어려운 여자들의 이중언어 속 메시지를 분석, 번역해주는 서비스를 제고해주고, 상황별 맞춤 대응 전략을 제안하는 번역 서비스
<br>
<img width="1920" height="1080" alt="제목을 입력하세요 1" src="https://github.com/user-attachments/assets/83052b9c-b161-494d-a1cc-4fcc0925178e" />

---

## 2. 서비스 소개
짧은 카카오톡/메신저 메시지에서 발생하는 남녀 간 의미 차이를 해석하고, 상대방의 의도를 분석하여 적절한 대응 문장을 제안해주는 서비스입니다.  
‘괜찮아’라는 단어가 실제로 괜찮다는 의미인지, 혹은 다른 마음을 내포하고 있는지 분석할 수 있습니다.
<img width="1920" height="1080" alt="제목을 입력하세요 3" src="https://github.com/user-attachments/assets/8e83082d-4c8e-4f12-a9eb-c30fe078636d" />

<img width="1920" height="1080" alt="제목을 입력하세요 4" src="https://github.com/user-attachments/assets/ced689bf-517e-4728-8200-2909ca7f3571" />
<img width="1920" height="1080" alt="제목을 입력하세요 5" src="https://github.com/user-attachments/assets/dc975397-688b-4ce8-90b3-1be273e1d093" />

---

## 3. 프로젝트 기간
2025년 7월 ~ 2025년 8.22 (약 2주)

---

## 4. 주요 기능
- 입력 문장의 감정 레벨 분석
- 남녀 간 의미 차이 해석
- 상황별 대응 문장 추천 (랜덤 3~4개 출력)
- 사용자 맞춤 반응 제안 기능

---

## 5. 기술 스택

<img width="1920" height="1080" alt="제목을 입력하세요 13" src="https://github.com/user-attachments/assets/c6ebb94f-f8d8-4a84-a9e7-a32f24e62c0d" />

## 🔧 기술 스택

## 🔧 기술 스택

**언어**  
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**프레임워크**  
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)

**DB**  
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![CSV](https://img.shields.io/badge/CSV-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

**서버**  
![Apache Tomcat](https://img.shields.io/badge/Tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=black)

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

![Uploading 제목을 입력하세요 16.png…]()


- **Front-End**: HTML, CSS, JavaScript 기반 화면 구성  
- **Back-End**: JSP & Servlet, Tomcat, Maven, CSV 데이터 처리  
- **Database 연동**: Oracle DB, MyBatis를 활용한 데이터 관리  
- **AI 분석**: OpenAI GPT-4o API를 통한 감정 분석 및 대응 문장 생성  

---

## 7. 서비스 흐름도

사용자 여정은 **회원가입/로그인 → 메인화면 → 기능 선택 → 결과/히스토리 관리**의 흐름으로 구성됩니다.

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
## 10. 시연 영상

https://github-production-user-asset-6210df.s3.amazonaws.com/224683260/483044320-ea1d59ca-85c7-47c0-aeb1-d77b98917170.mp4?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20250921%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20250921T040142Z&X-Amz-Expires=300&X-Amz-Signature=9a372d30f9cba9351b3070e624318812fb56e2add5b2b7aa2df44b59e567cf23&X-Amz-SignedHeaders=host

