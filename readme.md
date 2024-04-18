# 기본적인 git 사용법

## github.com 로그인
- 웹의 repository생성
- 우측 상단 [+] 클릭- New repository 클릭
![image](https://github.com/nanheelee/exam/assets/126562076/68160c05-39cb-4478-a16e-8b698ad7232a)

- 저장소 이름 입력 / public 선택
![image](https://github.com/nanheelee/exam/assets/126562076/6da09f45-3daa-47a4-9fde-2d2ea93f7043)

- 하단의 create repository 클릭


## local 초기 사용자 셋팅
- 설정 <br>
git config --global user.name "홍길동"<br>
git config --global user.email "sachory@gmail.com"<br>

- 확인<br>
git config user.name<br>
git config user.email<br>

## git 시작
git init

## staging 시키기

1) 파일 지정
- 원하는 파일 지정<br>
git add 파일명1 파일명2 

- 전체 파일 올리고 싶을때<br>
git add .

2) staging 올리기<br>
git commit -m '버전이름'

### repository에 등록
1) 내 git주소 변수로 등록<br>

git remote add origin https://github.com/nanheelee/exam.git

2) 내 깃으로 업로드<br>
git push -u <깃주소/변수> main<br>
git push -u origin main<br><br>

ex) git push -u https://github.com/nanheelee/exam.git main


### 결론

<셋팅><br>
git init<br>
git remote add origin https://github.com/nanheelee/exam.git<br><br>

<필요할 때마다><br>
git add <파일명><br>
git commit -m '버전이름'<br>
git push -u origin <브랜치이름><br>


## Branch 관련

1) 브랜치 생성
git checkout -b <브랜치이름>

2) 브랜치 확인
git branch

3) 현재 브랜치 이름 바꾸기
git branch -M <변경할이름>

4) 브랜치 변경 것
git switch <브랜치이름>


