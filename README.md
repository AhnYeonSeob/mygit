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
<p>🟡 이메일 또는 휴대폰으로 저장된 인증 수단을 해 인증번호를 요청할 수 있습니다.</p>
<p>🟡 인증요청 시, **JavaMailSender와 CoolSMS API를 연동**하여 실제 인증번호를 전송합니다.</p>

<h3>🎬 2차 인증응답페이지(2차인증요청시)</h3>
<img src="https://github.com/user-attachments/assets/7fcf380d-1870-4597-995d-e7ab3f2e9352" width="600px"/>
<p>🟡 인증번호 입력 후 서버에 검증 요청을 보내며, **세션 기반으로 인증상태를 유지**합니다. </p>
<p>🟡 인증이 완료되면 메인화면으로 자동 이동되며, 인증 실패 시 **에러 메시지 및 재전송 기능**도 제공합니다.</p>

<h3>🎬 메인화면(1,2차 인증 완료시)</h3>
<img src="https://github.com/user-attachments/assets/283384d3-7683-41c9-985d-730968985a0f" width="600px"/>
<p>🟡 로그인 완료 후 제공되는 **사용자별 대시보드 UI**입니다. - 🟡 학사일정, 과제, 게시판 등을 한 눈에 확인할 수 있습니다.</p>
<p>🟡 우측 하단 모듈에서 **드래그 앤 드롭 방식으로 레이아웃을 커스터마이징**할 수 있습니다. </p>

<h3>🎬 학사일정게시판(CRUD)</h3>
<img src="https://github.com/user-attachments/assets/ccd146f2-b578-41ab-90d1-eb91c3bd15cbf" width="600px"/>
<p>🟡 학생: 게시글 캘린더아이콘을 누르면 토글방식으로 FullCalendar를 통해 학사일정을 사용자별 일정관리캘린더에 추가/삭제 할 수 있습니다. </p>
<p>🟡 관리자: 게시글을 작성,조회,수정,삭제 할 수 있습니다. </p>

<h3>🎬 게시글 이미지업로드</h3>
<img src="https://github.com/user-attachments/assets/1dbdb471-96a2-47f4-a864-15f572df645c" width="600px"/>
<p>🟡 **CKEditor를 활용한 WYSIWYG 게시판 작성기**를 구현하였습니다.  </p>
<p>🟡 이미지 업로드는 Base64 대신 **서버에 업로드 후 URL 반환 방식(SimpleUploadAdapter)**으로 구현하여 **성능 개선과 보안 강화**를 동시에 고려했습니다. </p>

<h3>🎬 팀배정</h3>
<img src="https://github.com/user-attachments/assets/442d3362-3b35-4e1e-a306-f820405d9860" width="600px"/>
<p>🟡 Drag & Drop 방식의 직관적인 팀 배정 UI를 구현하여 사용자 편의성을 높였습니다.</p>
<p>🟡 수강생을 원하는 팀으로 드래그하거나 조장/일반 팀원 역할을 설정할 수 있습니다.</p>
<p>🟡 배정 시에는 MERGE 구문을 사용하여 Insert 또는 Update를 통합 처리함으로써 SQL 구문 최적화를 적용했습니다.</p>
<p>🟡 팀 구성 변경 시 즉시 반영되도록 비동기 처리(Ajax)와 상태 저장 로직을 연계하여 UX를 개선했습니다.</p>

---

## 📂 프로젝트 구조 (간단 예시)
