## 코로나 세계 현황판 만들기

Javascript로 만든 코로나 세계 현황판을 Typescript로 변환하는 프로젝트

![링크 시연 화면](./src/assets/img/covid-19-dashboard-demonstration.gif "링크 시연 화면")

## 자바스크립트 프로젝트에 타입스크립트 적용하기

0. 자바스크립트 파일에 JSDoc으로 타입 시스템 입히기 (Optional)
1. 타입스크립트의 기본 환경 구성
    - [x] NPM 초기화 (npm init-y)
    - [x] 타입스크립트 라이브러리 설치 (npm i typescipt -D)
    - [x] 타입스크립트 설정 파일 생성 (tsconfig.json 파일 생성)
    - [x] 자바스크립트 파일을 타입스크립트 파일로 변환하기 (파일 확장자 변경)
    - [x] `tsc`명령어로 타입스크립트 compile하기
2. 명시적인 `any` 선언하기
    - `tsconfig.json`파일에 `noImplicitAny`값을 `true`로 추가
    - 가능한 구체적인 타입으로 타입 정의
3. 프로젝트 환경 구성
    - babel, eslint, prettier 등의 환경 설정
4. 외부 라이브러리 모듈화
    - axios 라이브러리 설치 및 load
    - Chart.js라이브러리 설치 및 load

## 기술
- Javascript
- Typescript
- axios
- chart.js
- eslint

## 개발 환경
- [Chrome](https://www.google.com/intl/ko/chrome/)
- [Git](https://git-scm.com/downloads)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Node.js LTS 버전(v10.x 이상)](https://nodejs.org/ko/)

## 참고 api
- [Postman API](https://documenter.getpostman.com/view/10808728/SzS8rjbc?version=latest#27454960-ea1c-4b91-a0b6-0468bb4e6712)

## 참고 자료

- [존스 홉킨스 코로나 현황](https://www.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6)
