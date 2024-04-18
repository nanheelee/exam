# 기본적인 git 사용법

## github.com 로그인
- 웹의 repository생성

## local 초기 사용자 셋팅
- 설정
git config --global user.name "홍길동"
git config --global user.email "sachory@gmail.com"

- 확인
git config user.name
git config user.email

## git 시작
git init

## staging 시키기
- 원하는 파일 지정
git add 파일명1 파일명2 

- 전체 파일 올리고 싶을때
git add .

### 제목 3수준

git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/nanheelee/exam.git
git push -u origin main
