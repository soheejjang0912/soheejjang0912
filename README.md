 

<p>
  안녕하세요, <strong>장소희</strong>입니다.<br/>
  Java·Spring 기반의 웹/앱 서비스 개발 경험을 바탕으로 백엔드와 프론트엔드를 모두 경험해 왔습니다.<br/>
  사용자 요구를 빠르게 파악하고, 데이터 처리·시각화·API 설계를 통해 서비스의 효율과 가치를 높이는 개발자를 지향합니다.
</p>
 

---

## 🛠 기술 스택

| 구분 | 내용 |
| --- | --- |
| **백엔드** | Java(Spring), .NET(C#), REST API 설계·구현 |
| **프론트엔드** | JavaScript, jQuery, AJAX, HTML, CSS, Highcharts |
| **데이터베이스** | PostgreSQL, Microsoft SQL Server |
| **개발 도구** | Eclipse, Visual Studio, Android Studio, Git, SVN, SourceTree |
| **인프라/운영체제** | Linux(CentOS) + Apache Tomcat, Windows Server + IIS |
| **기타 경험** | Spring Batch, Docker, Jenkins, Redis, Kubernetes(기초) |

---

## 💼 경력

| 기간 | 회사 | 역할 요약 |
|:------:|:-----|:------------------|
| 2021.03 ~ 2024.10 | **㈜ 바스코아이씨티** | 에너지 관리 플랫폼(EMS) 풀스택 개발, 데이터 시각화/최적화, 통합 로그인 시스템 구축, 배포 문서화 |
| 2019.03 ~ 2020.05 | **㈜ Brastech** | C#·ASP.NET·VB6 기반 응용프로그램 개발·유지보수 (병원·물류·QR관리 등) |
| 2016.11 ~ 2018.04 | **㈜ 핸즈온러닝** | LEGO EV3/WEDO 코딩 교육, 교육 콘텐츠 개발 및 행사 운영 |

---

## 🚀 주요 프로젝트  

### 📊 Smart Building Platform (SBP)
- **기간**: 2021.12 ~ 2024.10  
- **개요**: 건물 내 **사용·발전·저장 에너지** 데이터를 통합 관리하고 시각화하여 에너지 효율을 분석하는 웹 플랫폼  
- **주요 업무**
  - **UI/UX 기획**: Figma·PPT로 화면 흐름 설계, 대시보드/분석/리포트 시각화 방식 정의
  - **프론트엔드**: JSP + jQuery + Highcharts 기반 대시보드 구현, AJAX 실시간 조회, 공통 팝업 모듈(검색/필터/선택) 설계
  - **백엔드**: eGovFrame(Spring MVC 3.10) 기반 Controller→Service→DAO 계층화, **REST API** 설계·구현
  - **데이터 처리**: PostgreSQL + iBATIS로 복합 조건 통계/분석 쿼리 작성, **인덱스 활용 및 쿼리 구조 단순화**로 응답 속도 최적화
  - **리포팅**: Apache POI 기반 **엑셀 보고서 자동 생성 모듈** 개발
  - **인증/권한**: Tomcat WAR 분리 구조, **JSESSIONID 기반 간이 SSO**, HttpSession으로 세션 관리, 권한별 메뉴/기능 분기
  - **안드로이드 앱**: WebView 접속 및 **접속 정보 설정/검증(비밀번호 확인·초기화)** 기능 개발
  - **문서화/배포**: 설치·시험 절차서, 초기 설정 가이드, 연계사 기술지원 대응
- **사용 기술**
  - Backend: Java, Spring(eGovFrame), PostgreSQL, iBATIS, Tomcat
  - Frontend: JSP, JavaScript, jQuery, HTML/CSS, Highcharts
  - 기타: Apache POI, Android Studio
- **대표 개선 포인트**
  - 복합 필터(에너지원/용도/기간) 조건 최적화로 **대용량 조회 응답 체감 속도 개선**
  - 반복 보고서 업무 자동화(엑셀 모듈)로 **운영 편의성 향상**

---

### ⚡ Total Operation Center (TOC)
- **기간**: 2021.05 ~ 2021.11  
- **개요**: 전력 계측기·태양광 등 설비에서 수집되는 **실시간 에너지 데이터**를 단일 화면에서 모니터링  
- **주요 업무**
  - JS/HTML UI 구축, **Highcharts 시계열 차트**로 사용·발전·저장량 시각화
  - .NET Framework 기반 **REST API** 및 MSSQL 데이터 처리
  - AJAX 기반 실시간 조회 및 반응형 UI 처리
  - 통합 테스트 시나리오, **WBS 작성** 등 산출물 정리
- **사용 기술**: C#, .NET Framework 4, MSSQL, JavaScript, Highcharts

---

### 🔌 EDS-M 연계 프로그램 (Electric Power Data Service Market)
- **기간**: 2021.08 ~ 2022.09  
- **개요**: 전력데이터 서비스 마켓 **Open API** 연계, **15분 단위·요금 데이터** 수집·가공 후 DB 저장하는 Windows Forms 앱  
- **주요 업무**
  - 사용자 설정 기반 API 호출 및 **JSON 파싱**
  - **정해진 주기(15분) 스케줄링** 데이터 수집·저장
  - MSSQL **정규화** 및 **중복 저장 방지 로직**
  - 네트워크 오류·비정상 응답 등 **예외 처리**
  - 배포용 설치 파일 제작, 설치/운영 매뉴얼 작성
- **사용 기술**: C#, .NET Framework 4.6.1, Windows Forms, MSSQL

---

### 💾 NAS Backup 파일 업로드 모듈
- **기간**: 2021.04  
- **개요**: DB 백업/로그 파일을 주기적으로 탐색해 **NAS 경로로 자동 업로드**하는 경량 Windows Forms 모듈  
- **주요 업무**
  - 파일명·크기 비교로 **중복 전송 방지**, 전송 상태 모니터링 및 예외 메시지 처리
  - **백그라운드 실행** 및 최소 UI로 자원 사용 최소화
- **사용 기술**: C#, .NET Framework, Windows Forms

