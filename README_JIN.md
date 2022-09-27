
## FF. Safari, Chrome, Edge 등 환경 체크

## Git 
GMAIL : de.jin.1031@gmail.com



git --version

---------------------------------------------------------------------------
git 설치 후,
사용자 정보 설정

$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com


Tailwindcss

WCAG관점에서 (웹접근성)지키기


*degit ; 특정파일만 카피하고 싶을 때

html5 living standard /업데이트

## WAR-ARIA(accebssibility Rich ...)
role(역할) 추가.
role="banner"
role="main"
role="group"

접근성, 사용성 다 중요.

##Naming : 추세 class 사용
파스칼 케이스(P.C)
케멜 케이스 (C.C)  mainContent
K.C               main-content
스네이크케이스     main_content


## git명령어
git log --oneline
$ git remote -v
$ git remote add lecture https://github.com/seulbinim/webcafeHTML5.git
$ git checkout main
$ git switch main
$ git merge --quit
$ git status
$ git add .
$ git push origin main


## HTML 4.01, XHTML 1.0 : HTML5는 둘 다 호환되지만
HTML Hint 

$ npm install --save-dev htmlhint
$ npm install 만 입력하면,,, 알아서 다운로드 됨.

markdown ; 구글서칭해서 문서 작성규칙 살펴보기

attribute: 속성 추가
  <div class="" lang="en">
property : css에서 갖고 있는 속성을 바꿈

## 폰트
Noto sans : 구글
spoqa hans : 애플
2폰트를 합쳐서 CJK : china, japan, korea


html, body {
  font-family: Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Roboto, "Helvetica Neue", "Segoe UI", "Apple SD Gothic Neo", "Noto Sans KR", "Malgun Gothic", "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", sans-serif;
}

serif // 바탕체
sans-serif // 고딕계열


min-height만 설정, 레이아웃 설계시 높이값은 고정으로 주지 않는다