# 인사관리시스템 프로젝트
## 프로젝트 소개
- 프로젝트 주제  
   사내 인사, 근태, 급여관리 업무수행을 지원하는 프로그램입니다.
- 프로젝트 선정이유  
   kt비즈메카 그룹웨어 서비스를 벤치마킹하여 인사등록/관리, 근태/휴가관리, 급여조회와 같은 기능들을 Spring MVC 개발 방식으로 구현해 보았습니다.
## 팀원구성  
김은송, 남수진, 배유나, 이강현, 최준영, 한승우
## 프로젝트 개발 기간  
### 2023.1.30 ~ 2023.3.3
1. 레퍼런스 사이트 선정
2. 담당 기능 선정, 요구사항정의서 작성
3. 데이터베이스 설계, ERD 생성
4. 클래스 디렉토리 설계 및 페이지 레이아웃 작업
5. 담당 화면 및 기능 구현
6. 테스트 및 디버깅
7. 최종 수정 및 보완
## 프로젝트 개발 환경
- OS : Window 10/11 64bit
- Framework : Spring Boot
- DB : Oracle, myBatis
- Build : Maven
- WAS : Apache Tomcat 9.0
- IDE : Eclipse
- Language : Java
- Front-End : HTML , CSS, Javascript, BootStrap 5.3.0, jquery 3.6.1
- Version Management : Git, Github
## ERD
![파이널erd](https://github.com/yunabb/final-project/assets/115030323/dba36647-2473-4f58-9106-e9ef5a7c6b9b)
- 사원번호는 1000번부터 시작함
## 담당기능
### 사용자&담당자 공통 기능
![1 근태등록](https://github.com/yunabb/final-project/assets/115030323/fc9667f3-2229-48a4-94d5-b7deb9207263)
- 로그인 후 출근, 퇴근 버튼을 클릭하여 근태정보를 기록하고 db에 저장합니다.

