<img src="https://capsule-render.vercel.app/api?type=waving&color=A9D0F5&height=150&section=header" />

# 🧚BUGCLEAN


### 목차
- 프로젝트 개요
- 개발 환경 및 도구
- 기능 구현


## 📂프로젝트 개요

> **프로젝트:** 방역업체_그룹웨어
>
> **기획 및 제작:** 허석훈, 윤상열, 박성제, 노지언
>
> **분류:** 팀 프로젝트
>
> **제작 기간:** 2024.3 ~ 2024.5
>
> **사용 기술:** SPRING BOOT
>
> **문의:** arark057@gmail.com

---
## 🛠️개발 환경 및 도구
![FRAMEWORK](https://img.shields.io/badge/FRAMEWORK-%23121011?style=for-the-badge)
![boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&amp;logo=springboot&amp;logoColor=white)

![LIBRARY](https://img.shields.io/badge/LIBRARY-%23121011?style=for-the-badge)
![jquery](https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white)
![LOMBOK](https://img.shields.io/badge/LOMBOK-FF5722?style=for-the-badge&amp;logo=LOMBOK&amp;logoColor=white)

![IDE](https://img.shields.io/badge/IDE-%23121011?style=for-the-badge)
![Spring Tool Suite 4](https://img.shields.io/badge/Spring%20Tool%20Suite%204-6DB33F?style=for-the-badge&amp;logo=Spring&amp;logoColor=white)
![VS](https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)
![DB](https://img.shields.io/badge/dbeaver-382923.svg?style=for-the-badge&amp;logo=dbeaver&amp;logoColor=white)

![DB](https://img.shields.io/badge/DB-%23121011?style=for-the-badge)
![DB](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=black)

![LANGUAGE](https://img.shields.io/badge/LANGUAGE-%23121011?style=for-the-badge)
![js](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![js](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white)
![js](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![js](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

![OS](https://img.shields.io/badge/OS-%23121011?style=for-the-badge)
![js](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)

![SERVER](https://img.shields.io/badge/SERVER-%23121011?style=for-the-badge)
![js](https://img.shields.io/badge/apache%20tomcat-F8DC75?style=for-the-badge&amp;logo=apachetomcat&amp;logoColor=black)

![HOSTING](https://img.shields.io/badge/HOSTING-%23121011?style=for-the-badge)
![js](https://img.shields.io/badge/Amazon_AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)

![OTHER](https://img.shields.io/badge/OTHER-%23121011?style=for-the-badge)
![js](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![js](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)

## 🖥️담당 기능 구현

### 1.사원 등록 요청
![1 사원등록 압축](https://github.com/nheris/algorithm/assets/147366904/428a33f0-7579-4728-8de8-81c32c061561)
- 유효성 검사를 통해 각 입력값 검증
- 인사팀 승인 후 로그인 가능

### 2.ID,PW 찾기
![2 아디비번찾기_1](https://github.com/nheris/algorithm/assets/147366904/63a7ff1b-38d9-4fbf-bb40-d6128e09b682)
- DB에 입력한 정보와 일치하는 사원이 존재 시 ID 정보 공개, 임시비밀번호 전송
- 선택에 따라 임시비밀번호 문자 or 이메일로 전송

### 3.로그인
![3 로그인](https://github.com/nheris/algorithm/assets/147366904/6d5d8419-7525-47a2-9dcc-7e14e4d08963)
- 이메일과 비밀번호 사용해 로그인, 퇴사자경우 계정 잠금
- JSP에 spring:message를 사용 로그인 실패 문구 확인

### 4.메인페이지
![4](https://github.com/nheris/algorithm/assets/147366904/f7695af8-1e33-444c-9db6-c3befb4de82f)
- 출/퇴근하기 버튼 클릭 시 DB에 출/퇴근 시간 INSERT 출/퇴근 시간 화면에 표시
- 최근 공지와 스케쥴에 대한 정보,위치 확인 가능

### 5.마이페이지
![5](https://github.com/nheris/algorithm/assets/147366904/9ba6e360-5796-46c7-a0f4-39aa029f122e)
- 사용자 정보 확인 및 수정
- 서명 등록 및 수정 가능

### 5.결재문서함
![6 결재문서함](https://github.com/nheris/algorithm/assets/147366904/ce3e23c7-6ace-444b-b3c2-be7bba78fcd4)
- 전체, 대기(시용자가 결재해야 할 문서), 진행(결재하였지만 최종 결재가 이루어지지 않은 문서), 완료(최종 결재 or 반려된 문서) 
- 카테고리별 결재 문서 확인 가능


<img src="https://capsule-render.vercel.app/api?type=waving&color=A9D0F5&height=150&section=footer" />
