# 메뉴 상세 화면

## 관련 API
[/menu/getAllMenu](https://github.com/lunch-team/lunch-rest-api/wiki/Menu#메뉴-상세-조회)  
[/menu/visitMenu](https://github.com/lunch-team/lunch-rest-api/wiki/Menu#메뉴-방문)  
[/menu/deleteMenu](https://github.com/lunch-team/lunch-rest-api/wiki/Menu#메뉴-삭제)  

## 설명
선택된 단일 메뉴를 조회한다.

## 기능
- 메뉴 정보 상세 조회
  - menuId가 없으면 메뉴 전체 메뉴 목록으로 이동
- ~~메뉴 수정~~
  - 메뉴 상세 다시 조회
- 메뉴 삭제
  - 성공시 더 이상 메뉴가 없으므로 전체 메뉴 목록으로 이동
- 방문 기록 추가
- 리뷰 작성 페이지 이동
- 리뷰 조회
  - 메뉴 정보 상세 조회에 포함되어 있음
  - 사진이 업로드 되어 있다면 사진도 해당 리뷰에 추가 
- 리뷰 삭제
  - 본인과 ADMIN만 가능