# GitHerb 프로젝트
#### IoT 기기 연동 & 웹·앱 식물 커뮤니티 풀스택 개발
<I> (Python, Java/Spring, React, React Native) </I>

<hr>

# 프로젝트 개요
GitHerb는 라즈베리파이와 각종 센서를 활용한 **스마트 식물 관리 시스템**과 **식물 애호가들을 위한 소셜 커뮤니티**를 결합한 풀스택 프로젝트입니다.

실시간으로 식물의 환경 데이터(온도, 습도, 조도, 토양습도)를 수집하고, 사용자가 웹과 앱에서 식물 상태를 확인하며 원격으로 워터펌프, LED, 팬 등을 제어할 수 있습니다. 또한 게시판, 채팅, 팔로우 등 커뮤니티 기능을 통해 다른 사용자들과 식물 키우기 경험을 공유할 수 있습니다.

<hr>

# 레포지토리
<table>
  <tr>
    <td>구분</td>
    <td>링크</td>
    <td>기술 스택</td>
  </tr>
  <tr>
    <td>App</td>
    <td><a href="https://github.com/duswn7740/app_plant_community">📱 github 바로가기</a></td>
    <td>React Native</td>
  </tr>
  <tr>
    <td>Frontend</td>
    <td><a href="https://github.com/duswn7740/frontend_plant_comunity">🎨 github 바로가기</td>
    <td>React</td>
  </tr>
  <tr>
    <td>Backend</td>
    <td><a href="https://github.com/duswn7740/backend_plant_comunity">⚙️ github 바로가기</td>
    <td>Java/Spring + MariaDB</td>
  </tr>
</table>

<hr>

# 기술 스택
Spring Boot 3.4 | Java 17 | MyBatis | MariaDB | WebSocket
<hr>



# 주요 기능
### 📅 식물 관리 캘린더 (담당 기능)
- **물주기 일정 관리**: 식물별 물주기 날짜 등록 및 자동 추천
- **관리 일기**: 물주기, 비료, 분갈이 등 관리 내역 기록
- **푸시 알림**: 물주기 시간 앱 푸시 알림 (React Native)

### 🌱 IoT 기반 식물 관리
- 실시간 환경 모니터링 (온도, 습도, 조도, 토양습도)
- 액추에이터 원격 제어 (워터펌프, LED, 팬)
- 자동/수동 제어 모드

### 👥 소셜 커뮤니티
- 게시판 (식물 자랑, 재배 팁, Q&A)
- 팔로우/좋아요/댓글
- 실시간 채팅 (WebSocket)

### 🌤️ 기타 기능
- 기상청 API 연동
- 크로스 플랫폼 지원 (Web + Mobile App)`,

<hr>

# 웹·앱 시연 영상

### 웹 시연
<!-- 회원가입 -->
https://github.com/user-attachments/assets/6d415387-ff98-462d-949e-39a2138518bc
<!-- 회원권한별 로그인 -->
https://github.com/user-attachments/assets/a87fb019-9874-4fce-aab0-a9e6caad27d0
<!-- 캘린더 -->
https://github.com/user-attachments/assets/c6da9b27-f67f-41f4-b873-b386ac0bb5c3


<hr>

### 앱 시연

<!-- 회원정보수정 -->
https://github.com/user-attachments/assets/749d713a-70d2-4656-9692-4893554e6cf2
<!-- 회원권한별 로그인 -->
https://github.com/user-attachments/assets/0fed67e2-0da9-4798-9179-92972ff551d4
<!-- 앱푸시알람 간이 -->
https://github.com/user-attachments/assets/6187bd3d-b7f0-4a54-9ccd-dff0ba23fcad

**Expo SDK 53부터 Expo Go에서는 푸시 알림을 지원하지 않음**
그래서 백엔드 콘솔로 대신 확인함


