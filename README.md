# SpringBoot-Project-KDT_Trainee_Managerment_System

SpringBoot + JSP를 이용한 통합 학 관리 시스템

## 프로젝트 소개

늘어나는 IT관련 학원의 학생들을 통합적으로 관리해주는 시스템

## 프로젝트 목적

- 학생 및 강사, 강의 등을 간편하게 관리할 수 있는 서비스 제공
- 시험 문제 배포 및 문제를 풀고 채점을 할 수 있는 서비스 제공
- 학생들끼리 방을 생성 및 입장하여 보드게임 형식의 코딩테스트 게임을 할 수 있는 환경 제공
- Bert 모델을 이용한 IT 관련 용어를 자동 수집해주는 용어사전 제공

## 개발 기간

- 2023-06-01 ~ 2023-06-13 (9일)

## 개발 인원

- 팀장 정윤재 - DB설계, 산출문서, 풀스텍 서브
- 팀원 유진상 - LMS(대시보드) 통합 화면 
- 팀원 이승주 - 사용자 관리 시스템 LMS 백앤드
- 팀원 최승만 - 관리자 시스템LMS 백앤드
- 팀원 박주형 - DB 구축

## 개발 환경

- Java 8
- JDK 1.8.0
- IDE : STS 4.18.1
- Framework : Springboot 3.0.3
- Database : MySQL
- ORM : Mybatis

## 주요 기능 및 화면

**메인화면**

- 과목 및 학생 리스트 출력
- 과목별 날짜 달력에 출력

<details>
<summary>더보기</summary>
  
![메인](https://github.com/Francisco95/KDT_trainee_management_system/assets/77893146/e3397dd0-fc43-4844-af17-5cb1d2bed3a4)
</details>

**회원가입**

- ID, Email 중복 체크
- 우편번호 찾기

<details>
<summary>더보기</summary>

![회원가입](https://github.com/Francisco95/KDT_trainee_management_system/assets/77893146/7e91dff7-7cb7-463d-8f6a-5858c5425aca)
</details>

**로그인**

- ID, Pwd 일치 확인
- ID, Pwd 찾기
- 로그인 세션 생성

<details>
<summary>더보기</summary>

![로그인](https://github.com/Francisco95/KDT_trainee_management_system/assets/77893146/d08b4abb-5d62-4e50-a77f-a25ea830d2a1)
</details>

**공지사항**

- 공지사항 리스트 최대 5개 출력
- 공지사항 등록

<details>
<summary>더보기</summary>
  
![공지사항](https://github.com/Francisco95/KDT_trainee_management_system/assets/77893146/a17954cf-dd92-4a1f-8a51-310fdbe53541)
</details>

**교육등록**

- 교육 등록 및 해당 교육 참여 학생 등록
- 시작일 및 종료일 등록
- 해당 교육에 포함된 과목 등록록

<details>
<summary>더보기</summary>
  
![교육등록](https://github.com/Francisco95/KDT_trainee_management_system/assets/77893146/401fd2b0-ffb9-48cd-82b3-17cf56394eb6)
</details>

**질의응답**

- 질문 등록 및 수정 삭제 기능
- 답변 등록 및 수정 삭제 기능
- 질문 삭제시 해당 질문에 답변 글 자동 삭제

<details>
<summary>더보기</summary>
  
![질의응답](https://github.com/Francisco95/KDT_trainee_management_system/assets/77893146/4cef019c-c9eb-497f-8270-61a804695c66)
</details>

**시험등록**

- 시험문제 등록 및 수정 삭제 기능
- 이미지 파일 업로드 기능

<details>
<summary>더보기</summary>
  
![시험등록](https://github.com/Francisco95/KDT_trainee_management_system/assets/77893146/979bcaf3-154b-4d93-8093-31e98a6068eb)
</details>

**시험결과**

- 푼 문제의 오답 체크 기능 및 점수 출력

<details>
<summary>더보기</summary>
  
![시험결과](https://github.com/Francisco95/KDT_trainee_management_system/assets/77893146/f5d7df79-09b8-41c7-9843-5c151a4ee239)
</details>
