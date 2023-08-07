# Servlet - Project - YAKAJA 
서블릿으로 구현한 호텔 예약 사이트

## 🏟 프로젝트 소개
야놀자, 여기어때 등을 참고한 호텔 예약 사이트입니다.
<br>

## ⏲ 개발 기간
* 2023.06.13일 ~ 2023.07.07일

### 👨‍💻 멤버 구성
- 조장 양상민 - 지역별/이름별 호텔 검색, 리뷰게시판(CRUD), 호텔예약, 예약정보 대조, Database Script 제작, 통합 및 형상관리, 객실 출력
- 조원1 박지애 - Database 데이터 입력, 호텔정보(호실 출력), 객실정보, ppt 제작 
- 조원2 정준엽 - header&footer, 관리자 기능(회원목록, 예약목록, 호텔목록), 업주 기능, 예약조회, 예약취소, 결제
- 조원3 지우림 - Database 데이터 입력, 로그인, 회원가입, id 찾기, pw 찾기, 호텔 등록, 회원탈퇴
- 조원4 최진규 - 지역별/이름별 호텔 검색, 검색결과 창 정렬기능, 리뷰 작성

### 🛠 개발 환경
- 'Java 11' <img src="https://img.shields.io/badge/java-007396?style=flat-square&logo=java&logoColor=white"/>
- 'JDK 11.0.18'
- **IDE** : Eclipse 2022-09
- **Database** : Oracle DB(18c) <img src="https://img.shields.io/badge/ORACLE-F80000?style=flat-square&logo=oracle&logoColor=white"/>
- **Server** : Tomcat 8.5 <img src="https://img.shields.io/badge/Apache Tomcat-F8DC75?style=flat-square&logo=apachetomcat&logoColor=black"/>

### 🔨 사용 기술
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=black">
<img src="https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jQuery&logoColor=white"/>
</br>

## 📌 주요 기능
#### 회원가입
- ID 중복 체크(Ajax) 

#### 로그인
- DB값 검증
- ID 찾기, PW 찾기
- 로그인 시 세션(Session) 생성

#### 마이 페이지
- 내 정보 수정
- 회원 탈퇴
- 예약정보 확인, 취소
  
#### 메인 페이지
- 지도 UI
- 리뷰 검색, 검색어 검색, 지역 검색기능 

#### 호텔 검색
- 검색어 검색, 지역 검색
- 이름순, 별점순 정렬

#### 예약 및 결제
- 객실선택(Ajax)
- 객실 정보
- 결제 API (포트원, Ajax)

#### 리뷰 게시판
- 리뷰작성, 게시판 목록, 읽기, 수정, 삭제(CRUD)
- 게시판 목록 페이징

#### 업주 페이지
- 호텔 등록
- 등록 호텔 확인
- 예약목록 확인

#### 관리자 페이지
- 회원 목록
- 호텔 목록
- 예약 목록

## DB 구성
![yakaja_ERD](https://github.com/hotel-yakaja/yakaja/files/12279524/yakaja_ERD.pdf)

