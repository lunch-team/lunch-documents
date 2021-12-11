# 아이디 찾기 / 비밀번호 재설정 화면

## 관련 API
[/auth/findId](https://github.com/lunch-team/lunch-rest-api/wiki/Member#아이디-찾기)  
[/auth/findPw](https://github.com/lunch-team/lunch-rest-api/wiki/Member#비밀번호-찾기-Step-1)  
[/auth/resetPassword](https://github.com/lunch-team/lunch-rest-api/wiki/Member#비밀번호-찾기-Step-2)

## 설명
사용자의 정보를 이용해서 아이디를 찾거나 비밀번호를 재설정하는 화면  
아이디 찾기와 비밀번호 재설정 화면을 별도의 2개 화면으로 분리해도 됨

## 기능
- 아이디 찾기
  - 회원가입 시 입력한 이메일과 이름으로 로그인 아이디 찾기
- 비밀번호 재설정
  - 회원가입 시 입력한 이메일과 로그인 아이디로 가입 정보가 있는지 확인 (memberId 반환됨)
  - 가입 정보가 있으면 새로운 비밀번호로 재설정
  - 이 때 새로운 비밀번호도 비밀번호 확인란이 있어야 함