# 2022년 10월 27일(목)~28일(금) 페어프로젝트

- 이동현, 유순일



## 프로젝트 목표

 페어 프로그래밍을 통한 영화 리뷰 커뮤니티 서비스를 개발합니다. 아래 조건을 만족해야 합니다.

- **CRUD** 구현(구현 방법 제한 없음)
- **Staticfiles** 활용 정적 파일(이미지, CSS, JS) 다루기
- Django **Auth** 활용 회원 관리(회원 가입 / 회원 조회 / 로그인 / 로그아웃)
- Media 활용 동적 파일 다루기
- 모델간 **1 : N / M : N 관계** 매핑



## FLOW

### 1. reviews 앱

- CRUD 구현
  - 로그인한 유저만 데이터 생성이 가능
  - 게시글 작성자  표시
- 댓글 기능
  - 댓글 작성 및 삭제
  - 로그인한 유저만 댓글 작성 가능
  - 해당 댓글 작성자만 삭제 가능
  - 댓글 작성자 표시
- 좋아요 / 좋아요 취소
  - 로그인한 유저만 좋아요 가능



### 2. accounts 앱 

- 회원가입
- 로그인
- 회원 탈퇴
- 회원정보 페이지
  - 팔로우 기능



### 3. 기타

- 네브바



## 진행상황

### 1. 13시 30분 ~ 14시 30분

- 이동현
  - review 앱에 CRUD 구현
- 유순일
  - base.html 작성
  - accounts 앱에서 회원가입,로그인,회원탈퇴,회원정보수정

