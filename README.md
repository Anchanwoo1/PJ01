# 🏥 병원정보 시스템 (Hospital Management System)

<img width="951" height="442" alt="Image" src="https://github.com/user-attachments/assets/f283bd58-656e-422d-84a6-71644594cc97" /> 

## 📌 프로젝트 개요
병원 내 진료 및 협진 관리, 환자 정보 관리, 고객센터 기능 등을 통합 제공하는 웹 기반 병원정보 시스템입니다.  
실제 의료 현장에서 발생할 수 있는 예약, 협진, 환자 관리 프로세스를 구현하여 병원 업무 효율성을 높이는 것을 목표로 개발하였습니다.  

---

## ⚙️ 기술 스택


**Frontend**  
![JSP](https://img.shields.io/badge/JSP-blue?logo=java&logoColor=white) 
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?logo=jquery&logoColor=white)

**Backend**  
![Java](https://img.shields.io/badge/Java-007396?logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?logo=spring&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-000000?logo=databricks&logoColor=white)

**Database**  
![Oracle DB](https://img.shields.io/badge/Oracle-F80000?logo=oracle&logoColor=white)

**Server**  
![Tomcat](https://img.shields.io/badge/Tomcat-F8DC75?logo=apachetomcat&logoColor=black)

**IDE/Tools**  
![Eclipse](https://img.shields.io/badge/Eclipse%20IDE-2C2255?logo=eclipseide&logoColor=white)
![STS](https://img.shields.io/badge/STS-6DB33F?logo=spring&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)


---

## ✨ 주요 기능
- **환자 관리**
  - 환자 등록 / 조회 / 수정
  - 예약 현황 관리
- **의료진 기능**
  - 협진 요청/수락/거절
  - 진료 기록 관리
- **관리자 기능**
  - 병원 부서 관리
  - 사용자 권한 관리
- **고객센터**
  - 칭찬 릴레이 게시판 
  - 문의/공지사항 관리
- **관리자 기능**
  - 의료진 및 협진의 가입 요청 승인 및 계정 관리
  - 환자 정보, 진료 및 협진 기록 등 사용자 데이터 통합 관리

---
 ## 🗂️ ERD (Entity Relationship Diagram)

병원정보 시스템에서 사용되는 주요 테이블과 관계 구조를 정리한 ERD입니다.

<img width="1930" height="1417" alt="Image" src="https://github.com/user-attachments/assets/43e8f11e-e748-44cf-bcf3-eaa845bbfd7d" />

---

🖼️ 주요 화면 (Screenshots) 
<table>
  <tr>
    <td align="center">예약 </td>
    <td align="center">예약 완료</td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/cc51e726-db4c-41a5-8fa0-4fcdef4616eb" width="550"></td>
    <td><img src="https://github.com/user-attachments/assets/bc63baa6-cadc-4bf3-9a9d-3ed3afaa2fc2" width="550"></td>
  </tr>
</table>

<table>
  <tr>
    <td align="center">증명서 발급 신청</td>
    <td align="center">증명서 발급</td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/e944ce3e-81e0-4e7f-bb34-67e68bcea3ad" width="550"></td>
    <td><img src="https://github.com/user-attachments/assets/f6574d38-81c7-4581-9e94-c7c55e385ae5" width="550"></td>
  </tr>
</table>
<table>
 <table>
  <tr>
    <td align="center">의료진 기능</td>
    <td align="center">관리자 대시보드</td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/eacc6116-7f46-4cc1-a4f9-110dca9356bf" width="550"></td>
    <td><img src="https://github.com/user-attachments/assets/e3dae107-381e-457d-955f-4cc11ff46955" width="550"></td>
  </tr>
</table> 

---

🛠️ 추가 적용 기술

- **SHA-512 암호화**
  - 사용자 비밀번호를 안전하게 저장하기 위해 SHA-512 적용

- **카카오 로그인**
  - 카카오 OAuth 인증을 이용한 간편 로그인 기능 제공

- **카카오 지도 API**
  - 병원 위치 표시 및 주소 기반 지도 조회 기능 구현

- **Highcharts**
  - 관리자 대시보드의 통계 데이터를 그래프 · 차트 형태로 시각화

- **네이버 스마트에디터**
  - 공지사항 및 게시판 작성 시 리치 텍스트 편집 기능 제공
