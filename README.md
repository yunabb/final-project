# 인사관리시스템 프로젝트
## :mega: 프로젝트 소개
- 프로젝트 주제  
   사내 인사, 근태, 급여관리 업무수행을 지원하는 프로그램입니다.
- 프로젝트 선정이유  
   kt비즈메카 그룹웨어 서비스를 벤치마킹하여 인사등록/관리, 근태/휴가관리, 급여조회와 같은 기능들을 Spring MVC 개발 방식으로 구현해 보았습니다.
## :raised_hands: 팀원구성  
김은송, 남수진, 배유나, 이강현, 최준영, 한승우
## :calendar: 프로젝트 개발 기간  
### 2023.1.30 ~ 2023.3.3
1. 레퍼런스 사이트 선정
2. 담당 기능 선정, 요구사항정의서 작성
3. 데이터베이스 설계, ERD 생성
4. 클래스 디렉토리 설계 및 페이지 레이아웃 작업
5. 담당 화면 및 기능 구현
6. 테스트 및 디버깅
7. 최종 수정 및 보완
## :computer: 프로젝트 개발 환경
- OS : Window 10/11 64bit
- Framework : Spring Boot
- DB : Oracle, myBatis
- Build : Maven
- WAS : Apache Tomcat 9.0
- IDE : Eclipse
- Language : Java
- Front-End : HTML , CSS, Javascript, BootStrap 5.3.0, jquery 3.6.1
- Version Management : Git, Github
## :floppy_disk: ERD
![파이널erd](https://github.com/yunabb/final-project/assets/115030323/dba36647-2473-4f58-9106-e9ef5a7c6b9b)
#### 유의사항
- DB 등록시 사원번호는 1000번부터 시작해야함
## 👩‍💻 담당기능
### 사용자&관리 공통 기능
#### 1. 근태등록
![1 근태등록](https://github.com/yunabb/final-project/assets/115030323/fc9667f3-2229-48a4-94d5-b7deb9207263)
- 로그인 후 출근, 퇴근 버튼을 클릭하여 근태정보를 기록하고 db에 저장
#### 2. 근태조회
![2 일일조회](https://github.com/yunabb/final-project/assets/115030323/9a190d02-c727-4509-bce5-30671e0c89dd)
- 근무일자를 지정하여 근태정보를 조회
- 출근시간, 퇴근시간, 휴일근로시간, 연장근로시간, 야간근로시간을 조회
#### 3. 월간근태조회
![6 월조회](https://github.com/yunabb/final-project/assets/115030323/56341e40-f777-4bd3-8b31-adacfbfc2f72)
- 근무년월을 지정하여 월근태정보를 집계하여 조회
- 관리자는 전 사원의 정보를 조회
### 관리자 기능
#### 1. 사용자들의 근태조회
![3 전사원조회](https://github.com/yunabb/final-project/assets/115030323/584d668f-b6c5-4f6f-a7ab-b490eee5a136)
- 전 사원들의 근태정보를 근무일자, 사원번호, 직급, 부서를 지정하여 조회
#### 2. 근태수정
![4 수정](https://github.com/yunabb/final-project/assets/115030323/b773a896-6796-43fb-b65b-01c08c8a7531)
- 근무시간을 수정
- 근무시간을 수정하면 시간이 다시 계산되어 적용
#### 3. 근태엑셀파일다운로드
![5 엑셀](https://github.com/yunabb/final-project/assets/115030323/64d9ffc5-2d28-4d9e-9d97-9ef5afed7423)
- 우측상단의 근태엑셀다운로드버튼을 누르면 조회한 근태정보가 엑셀표로 다운로드
