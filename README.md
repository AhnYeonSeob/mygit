<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rounded&color=0:5e6eba,100:2f5f92&height=120&text=LMS(Learning%20Management%20System)PROJECT&animation=&fontColor=ffffff&fontSize=40" />
</div>

## 📌 Info  
🟡 기존 교직원의 행정업무에 치중된 시스템을 개선하여, 학사 관리 측면에서 **사용자 중심의 편의성과 교육 환경의 질** 향상에 중점을 두었습니다.  
🟡 학적관리, 수강신청, 수업자료 및 과제관리, 출결관리 등 **직관적인 UI/UX 기반의 통합 학사관리 기능**을 구현하였습니다.  
🟡 **FullCalendar, Chart.js, WebSocket 등**을 활용하여 **데이터 시각화 및 실시간 협업 기능**까지 제공하며, 운영 효율을 극대화하였습니다.  

---

## 🛠️ Tech Stack

<div align="center">
  <img src="https://img.shields.io/badge/Java-007396?style=flat&logo=Java&logoColor=white">
  <img src="https://img.shields.io/badge/Spring-6DB33F?style=flat&logo=Spring&logoColor=white">
  <img src="https://img.shields.io/badge/Apache Tomcat-F8DC75?style=flat&logo=Apache Tomcat&logoColor=white">
  <img src="https://img.shields.io/badge/Oracle-F80000?style=flat&logo=Oracle&logoColor=white">
  <br/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=HTML5&logoColor=white">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=CSS3&logoColor=white">
  <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=flat&logo=Bootstrap&logoColor=white">
  <img src="https://img.shields.io/badge/Javascript-F7DF1E?style=flat&logo=Javascript&logoColor=black">
  <img src="https://img.shields.io/badge/jQuery-0769AD?style=flat&logo=jQuery&logoColor=white">
  <br/>
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=Figma&logoColor=white">
</div>

---

## 🧩 주요 기능

- ✅ 학사일정 캘린더 (FullCalendar API)
- ✅ 게시판 CRUD (CKEditor + 파일 첨부)
- ✅ 과제 피어리뷰, 채점 기능
- ✅ 실시간 팀 채팅 (WebSocket + STOMP + SockJS)
- ✅ 자동/수동 팀 배정 기능
- ✅ 2차 인증 (JavaMail + CoolSMS)
- ✅ 데이터 시각화 (Chart.js)

---

## 🖥 Service UI

<h3>🎬 1차 인증(로그인페이지)</h3>
<img src="https://github.com/user-attachments/assets/fd754eeb-c14d-4087-aa43-3ef72d00967b" width="600px"/>
<p>🟡 사용자는 입학 시 주어진 학번과 일정규칙으로 조합된 비밀번호(최초 로그인 이후 변경)를 입력하고 로그인 할 수 있는 페이지입니다.</p>

<h3>🎬 2차 인증요청페이지(로그인성공시)</h3>
<img src="https://github.com/user-attachments/assets/4b3cbcf0-66d3-46a4-a10d-9930d36b91fd" width="600px"/>
<p>🟡 이메일 또는 휴대폰으로 인증 수단을 선택해 인증번호를 요청할 수 있습니다.</p>

<h3>🎬 2차 인증응답페이지(2차인증요청시)</h3>
<img src="https://github.com/user-attachments/assets/7fcf380d-1870-4597-995d-e7ab3f2e9352" width="600px"/>
<p>🟡 전송된 인증번호를 입력하고 인증을 완료하면 메인 페이지로 이동할 수 있습니다.</p>

<h3>🎬 메인화면(1,2차 인증 완료)</h3>
<img src="https://github.com/user-attachments/assets/283384d3-7683-41c9-985d-730968985a0f" width="600px"/>
<p>🟡 로그인 완료 후 사용자별 대시보드가 제공되며, 학사일정과 게시판, 과제정보 등을 통합 관리할 수 있습니다.</p>




---

## 📂 프로젝트 구조 (간단 예시)
