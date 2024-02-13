# YourAccommodation

```
YourAccommodation 은 숙박 예약 프로젝트입니다
```

<br>

## View

<br>

## [목차]
1. [링크](#1-링크)
2. [개발 환경](#2-개발-환경)
3. [기능](#3-기능)
4. [프로젝트 설계](#4-프로젝트-설계)

<br>

## 1. 링크

<!-- - [1](https://www.notion.so/) -->

<br>

## 2. 개발 환경
```
각각의 프레임워크로 같은 기능을 개발합니다
```

### 2-1. Flask
```
alembic==1.13.1
blinker==1.7.0
click==8.1.7
colorama==0.4.6
dnspython==2.5.0
email-validator==2.1.0.post1
Flask==3.0.2
Flask-Login==0.6.3
Flask-Migrate==4.0.5
Flask-SQLAlchemy==3.1.1
Flask-WTF==1.2.1
greenlet==3.0.3
idna==3.6
itsdangerous==2.1.2
Jinja2==3.1.3
Mako==1.3.2
MarkupSafe==2.1.5
python-dotenv==1.0.1
SQLAlchemy==2.0.26
typing_extensions==4.9.0
Werkzeug==3.0.1
WTForms==3.1.2
```

### 2-2. Django

- Django

### 2-3. FastAPI

- FastAPI

### 2-4. Next.js

- Next.js

### 2-5. common

- Docker
- Redis
- PostgreSQL
- React
- TailwindCSS

<br>

## 3. 기능

- 회원가입
- 로그인 / 로그아웃
- 프로필
- 검색
- 예약
- 채팅
- 게시판
- 게시글
- 언어
- 사이트 정보

<br>

## 4. 프로젝트 설계

### 4-1. ERD

<!-- ![YourAccommodation ERD]() -->

### 4-2. Infra Architecture

<!-- ![YourAccommodation Infra]() -->

### 4-3. 기능 상세
- 로그인
    - 로그인 페이지
    - 회원가입
    - 로그인 / 로그아웃
- 프로필
    - 유저
        - 개인코드, 찜, 좋아요, 댓글, 팔로잉 목록
    - 사업자
        - 숙박 등록 리스트, 협업 사업자
- 채팅
    - 유저
        - 소모임 숙박 예약 채팅
    - 사업자
        - 협업 채팅
- 숙박
    - 검색
    - 게시판
        - 숙박게시글, 평점
    - 예약
        - 체크인 / 체크아웃, 지역, 최종가격
- 언어
    - 한국어, 영어
- 푸터
    - 사이트 정보

<br>

## 개발자

- Deeklming

<br>
