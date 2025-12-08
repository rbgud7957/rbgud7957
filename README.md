

##   🙌 소개
- 이름: 이규형 / Lee Gyue Hyeong
- 생년월일: 2001.05.18
- 소속: 한림대학교 정보과학대학 소프트웨어학부 스마트IoT 전공 / 빅데이터 복수전공
- Email: r67890@naver.com , rbgud7957@gmail.com
- 블로그: https://rbgud7957.github.io/

<br>

<div style="text-align: left;">
    <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> 🛠️ 기술 스택 </h2> <br> 
    <div style="margin: ; text-align: left;" "text-align: left;"> <img src="https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=Android&logoColor=white">
          <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=Firebase&logoColor=white">
          <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=Git&logoColor=white">
          <img src="https://img.shields.io/badge/Github-181717?style=flat-square&logo=Github&logoColor=white">
          <br/><img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=HTML5&logoColor=white">
          <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=Java&logoColor=white">
          <img src="https://img.shields.io/badge/Javascript-F7DF1E?style=flat-square&logo=Javascript&logoColor=white">
          <img src="https://img.shields.io/badge/Node.js-339933?style=flat=square&logo=node.js&logoColor=white">
          <br/><img src="https://img.shields.io/badge/MongoDB-47A248?style=flat=square&logo=mongodb&logoColor=white">
          <img src="https://img.shields.io/badge/Mongoose-880000?style=flat=square&logo=mongoose&logoColor=white">
          <img src="https://img.shields.io/badge/JWT-000000?style=flat=square&logo=jsonwebtokens&logoColor=white">
          <br/></div>
    </div>
    

## 📚 수강 과목
<details><summary>전공
</summary>

- 논리설계및실험
- 이산구조론
- 선형대수
- 자바프로그래밍I
- 자바프로그래밍II
- C프로프래밍
- C++프로그래밍
- 파이썬과학프로그래밍기초
- 소프트웨어개론
- 신호및시스템
- 데이터사이언스기초
- 디지털신호처리
- 통신네트워크시스템
- 오픈소스하드웨어응용
- 운영체제
- 자료구조
- IOT네트워크
- 정보보호론
- 네트워크보안
- 데이터베이스시스템
- 모바일센서공학
- 소프트웨어캡스톤디자인
- SW창업전략과펀딩
- 소프트웨어특강I
- 인공지능생체시스템개론
- 인공지능수학
- 컴퓨터네트워크
- 인공지능기초

</details>

<br>


## 💻 프로젝트

---

## 💱 실시간 환율 조회 시스템 (개인) 🔎 [깃허브](https://github.com/rbgud7957/IoT-Project)
⏰ 기간: 2024.05.31 ~ 2024.06.21

⚙️ 기술 스택: Java, Node.js, MongoDB, HTML/CSS, MQTT, Socket.IO

공공데이터포털 API를 활용해 실시간 환율(USD 기준)을 수집하고, MQTT를 통해 발행 → 구독 구조로 MongoDB에 저장하며, 웹페이지에서 실시간으로 시각화한 프로젝트

Java로 MQTT Publisher 구현 (환율 데이터 발행)

Node.js로 Subscriber + DB 연동 + Socket.IO 구성

MongoDB에 국가명 / 화폐명 / 환율 컬렉션 구분 저장

HTML 페이지에서 실시간 데이터 표시


![Image](https://github.com/user-attachments/assets/d55bcd31-138a-474e-8d5d-926889ad88f1)


---

## 💊 영양제 복용 관리 애플리케이션 (TEAM) 🔎  [깃허브](https://github.com/rbgud7957/Nutriwish.git)
- *2024.09.06 ~ 2024.11.22*

- 사용자들이 더 나은 건강을 유지하며, 자신의 건강 상태에 맞는 영양제 복용을 선택하고 관리할 수 있는 실용적인 애플리케이션

- ⚙️ 기술 스택: Android, HTML, CSS, JAVA, Firebase
  
  - 애플리케이션의 CSS 일부 구현
  - SpringBoot를 이용한 서버 만들다가 Firebase로 변경 + Firebase 연동
  - 서버 및 데이터베이스 관리
 
![image](https://github.com/user-attachments/assets/3a7981ef-e881-4a04-acc8-f386025b0ad9)

---

## 🏠 똑똑 스마트 홈 (TEAM) 🔎 [깃허브](https://github.com/rbgud7957/Smarthome.git)

📅 프로젝트 기간
2023.11.03 ~ 2023.11.29

💡 프로젝트 개요
Arduino UNO Board와 다양한 센서, 액추에이터(서보모터, LED, LCD, 피에조 스피커 등)를 이용하여 스마트홈 모형을 제작했습니다.

🛠 기술 스택
Arduino UNO Board

센서 및 액추에이터: 초음파 센서, 조도 센서, 부동 센서, 인체 감지 센서, 피에조 스피커, 서보모터, LED, LCD, 버튼(스위치)

개발 환경: Arduino IDE
<br>

🗂 주요 기능
<br>
- 스위치를 이용해 집 내부의 전등 ON/OFF 제어

- 인체 감지 센서를 통해 사람이 현관 앞에 서면 자동으로 불이 켜짐

- 초음파 센서를 통해 거리가 가까워질수록 피에조 스피커로 경고음이 나며 LED가 점등하면 주차완료

- 빛을 감지하고 자동으로 닫히는 커튼

- 일정 온도 이하로 떨어지면 자동으로 켜지는 보일러

![Image](https://github.com/user-attachments/assets/90ce012e-542c-402f-9879-94495b84568a)

<br>

---

## 📝 To-Do 관리 애플리케이션 (개인 프로젝트) 🔗 [깃허브](https://github.com/rbgud7957/Todo-app)

### 📅 2025.10 ~ 2025.11
개인별 로그인 기반으로 할 일을 생성·관리하고,  
카테고리 / 우선순위 / 마감일을 기준으로 정렬 · 필터링 · 통계 기능을 제공하는  
풀스택 Todo 웹 애플리케이션입니다.


## 🧰 기술 스택

- **Frontend:** Next.js, Tailwind CSS, Axios  
- **Backend:** Node.js, Express.js, RESTful API  
- **Database:** MongoDB + Mongoose  
- **Auth:** JWT, bcrypt  
- **Deploy:** Vercel(프론트), Render(백엔드), MongoDB Atlas(DB)


## 🚀 구현 기능 요약

### 🔐 회원 인증 기능
- 회원가입 / 로그인 / 로그아웃  
- JWT 인증 및 토큰 검증  
- 비밀번호 암호화(bcrypt)  
- 사용자별 Todo 데이터 분리 저장  
- 인증 여부에 따라 페이지 접근 제한(Protected Route)


### 📝 Todo 관리 기능 (CRUD)
- 할 일 생성(Create)  
- 할 일 조회(Read) – 로그인한 사용자 기준  
- 할 일 수정(Update) – 제목, 우선순위, 카테고리, 마감일  
- 할 일 삭제(Delete)  
- 검색 + 필터 + 정렬 + 페이징 기능 지원  


### ☁️ 배포 환경
- Next.js 프론트엔드 → Vercel 자동 빌드 & 배포 
- Express 백엔드 → Render 서버 호스팅
- MongoDB Atlas → 클라우드 DB 운영  
- `.env` 파일로 JWT Secret, DB URI 등 환경 변수 관리  

---
