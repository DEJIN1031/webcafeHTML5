
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

## WAI-ARIA(accebssibility Rich ...)
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
- markdown : 구글서칭해서 문서 작성규칙 살펴보기

```bash
$ npm install --save-dev htmlhint
$ npm install 만 입력하면,,, 알아서 다운로드 됨.
```


attribute: 속성 추가
  <div class="" lang="en">
property : css에서 갖고 있는 속성을 바꿈

## 폰트
- Noto sans : 구글
- spoqa hans : 애플
- 2 폰트를 합쳐서 CJK : china, japan, korea
- serif 바탕체 /sans-serif 고딕계열

```bash
html, body {
  font-family: Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Roboto, "Helvetica Neue", "Segoe UI", "Apple SD Gothic Neo", "Noto Sans KR", "Malgun Gothic", "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", sans-serif;
}
```



min-height만 설정, 레이아웃 설계시 높이값은 고정으로 주지 않는다

# 논리적인 순서
- viwe와 상관없이 논리적인 순서로 배치(설계)

# aria
- aria-label="true"
- aria-hidden="true"
**
## 음성명령에 대한 생각을 하고, alt를 넣어야 함
## 레이블에도 순위가 있다.

```css
ul.memver-service>li*>a[href="/"]
ul.member-service>li*>span[aria-hidden="true"]{:}+a[href="/"]
```

## BFC(block Formatting context)

## WCAG
- 인식의 용이성 : alt
- 운용의 용이성 : 키보드
- 이해의 용이성 : 제목, 기본언어
- 견고성 : 문법준수

## Core Web Vitals
- [WEB 바이탈](https://web.dev/i18n/ko/vitals/)
- Largest Contentful Paint(최대 콘텐츠풀 페인트, LCP): 
- First Input Delay(최초 입력 지연, FID)
- Cumulative Layout Shift(누적 레이아웃 시프트, CLS)

## CSS Sprite 기법
- 한장의 이미지에 여러 아이콘을 모아둠
- 성능이슈로 인해 사용하는 기법
