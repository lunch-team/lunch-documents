# "점심 뭐 먹지" 서비스의 개발문서
"점심 뭐 먹지" 서비스의 필요한 기능을 화면 관점으로 작성

## 화면 구성
- 메인
  - [메뉴 목록 조회 화면](https://github.com/lunch-team/lunch-documents/blob/main/Menu/menu-list.md)
    - [메뉴 상세 조회 화면](https://github.com/lunch-team/lunch-documents/blob/main/Menu/menu-detail.md)
      - [메뉴 추가 화면](https://github.com/lunch-team/lunch-documents/blob/main/Menu/menu-add.md)
      - [메뉴 수정 화면 ](https://github.com/lunch-team/lunch-documents/blob/main/Menu/menu-modify.md)
      - [리뷰 등록 화면](https://github.com/lunch-team/lunch-documents/blob/main/Menu/menu-review-add.md)
  - [랜덤 메뉴 조회 화면](https://github.com/lunch-team/lunch-documents/blob/main/Menu/menu-list-random.md)
  - [방문 기록 조회 화면](https://github.com/lunch-team/lunch-documents/blob/main/Menu/menu-log.md)
  - [로그인 화면](https://github.com/lunch-team/lunch-documents/blob/main/Member/member-login.md)
    - [회원가입 화면](https://github.com/lunch-team/lunch-documents/blob/main/Member/member-signup.md)
    - [아이디 및 비밀번호 찾기 화면](https://github.com/lunch-team/lunch-documents/blob/main/Member/member-findIdPw.md)

## 문서 작성 양식 
```md
# 메뉴 목록 화면

## 관련 API
[/menu/getAllMenu](https://github.com/lunch-team/lunch-rest-api/wiki/Menu#모든-메뉴-조회)

## 설명
등록된 전체 메뉴를 조회한다.

## 기능
- 메뉴 리스트 조회
- 정렬 타입 선택 기능 (가나다, 방문수 순, 방문일자 순)
- 정렬 오름차순, 내림차순 토글 기능
```