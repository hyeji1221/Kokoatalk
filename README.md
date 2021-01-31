# Kokoatalk
### Chatting Web using node.js
#### with LAH1203(Frontend - UI, UX, View), hyeji1221(Backend - Server, DB)

### 목차
1. [구현 목록](#구현-목록)
    1. [로그인](#로그인)
    2. [회원가입](#회원가입)
    3. [친구 목록](#친구-목록)
    4. [친구 검색 및 추가](#친구-검색-및-추가)
    5. [채팅](#채팅)
    6. [서버](#서버-생성)
    7. [데이터베이스](#데이터베이스)
    8. [기타](#기타)
2. [다음 주까지 만들어야 할 목록](#다음주까지-해야할-목록)

## 구현 목록
### 로그인
  - 로그인 창 구현 ver1 - 이아현 (2020-12-30)
    + login_page.html, login.js
  - mysql 이용 로그인 구현 ver1 - 임혜지 (2021-1-3) 
  - 회원가입 버튼 클릭시 회원가입 페이지로 넘어가는 기능 추가 ver2 - 이아현 (2021-01-04)
  - 로그인 성공/실패 페이지 및 링크 추가 ver1 - 이아현 (2021-01-24)
    + login_success.pug, login_fail.pug

### 회원가입
  - mysql 이용 사용자 추가 기능 구현 ver1 - 임혜지 (2021-1-3)
  - 회원가입 창 구현 ver1 - 이아현 (2021-01-04)
    + signup_page.html
  - 회원가입 성공/실패 창 구현 ver1 - 이아현 (2021-01-04)
    + signup_success.html, signup_fail.html
  - 회원가입 조건 구현 ver1 - 이아현 (2021-01-16)
    + signup.js
  - 회원가입 조건 일부 변경 ver2 - 이아현 (2021-01-19)
  - 회원가입 성공/실패 페이지 및 링크 추가 ver1 - 이아현 (2021-01-24)
    + signup_success.pug, signup_fail.pug

### 친구 목록
  - 친구 목록 페이지 샘플 코드 작성 ver1 - 이아현 (2021-01-16)
    + friend_list_page.html
  - 친구 이름 배열과 연결되도록 코드 추가 ver2 - 이아현 (2021-01-18)

### 친구 검색 및 추가
  - 친구 검색 및 추가 페이지 ver1 - 이아현 (2021-01-22)
    + add_friend_page.pug, search_add_user.js
  - 사용자 검색 알고리즘 ver1 - 이아현 (2021-01-22)
    + 완벽히 일치할 경우만 나오도록 구현
  - 사용자 검색 알고리즘 ver2 - 이아현 (2021-01-23)
    + 일부만 일치해도 검색 결과에 나오도록 구현
    + 단, 자음이나 모음만 일치해서는 안되고, 한 글자가 구성될 때 완전히 일치해야 함
  - 친구 검색 및 추가 페이지 ver2 - 이아현 (2021-01-23)
    + 친구 검색 및 추가 버튼 클릭 시 제대로 실행되지 않던 오류 해결
    + 답은 매개변수 처리 방식이었다. (참고: https://iamdaeyun.tistory.com/entry/pug-%EB%AC%B8%EB%B2%95-input-value)
  - 친구 추가 성공/실패 페이지 및 링크 추가 ver1 - 이아현 (2021-01-24)
    + add_friend_success.pug, add_friend_fail.pug

### 채팅

### 서버 생성
  - createServer ver1 - 임혜지 (2021-1-3)
    + 외장 모듈 설치(package-lock.json)

### 데이터베이스
  - 연결
    + 로그인
    + 회원가입
    + 친구 목록
  - 내부 구조
    + 본인 이메일, 비밀번호, 이름
    + 친구 목록

### 기타
  - CSS update ver1 (2020-12-30)
  - main.js에 html 코드 연결
    + 이아현 (2021-01-16)
  - html 코드 pug로 변경 후 작성 - 이아현 (2021-01-16)
  - CSS update ver2 (2021-01-31)
    - CSS update ver2.0
    - CSS update ver2.1

## 다음주까지 해야할 목록
### 혜지
  - mysql 외부 접속 허용
  - 로그인, 회원가입 mysql 연결 복원
  - 데이터베이스 구조 바꾸기
  - 친구목록, 사용자목록 연동하기
### 아현
  - css 꾸미기
