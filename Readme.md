## 프로젝트 생성 
▶`npx create-expo-app -t expo-template-blank-typescript`<br>
▶기존 javascript로 구성한 컴포넌트를 typescript로 변환한다.(js파일을 모두 tsx파일로 변환)<br>

## typescript 테스트 

▶json의 scripts에 test:typescript:"tsc"추가  ->`npm run test:typescript`실행<br>

## 아이콘 설치

▶` npm install @expo/vector-icons `<br>

## TypeScript변환 

▶children들은 reactElement로 받아준다.<br>
▶TypoGraphy를 import 하기위해 count의 유무를 판별하여 prop으로 받아준다.<br>

## ESLint 

▶문법상 에러를 먼저 검출 해 낼 수 있는 도구 <br>
▶Typescript와 함께 많이 사용됨 <br>
▶`http://airbnb.io.javascript` -> 에어비엔비 ESLint<br>
▶prettier = 코딩스타일을 변환 해주는 tool -> `http://prettier.io`<br>

## ESLint 적용

▶`npm install --save-dev eslint` 
▶`npx eslint init`
▶`npm run test:lint` -> 린트로 테스트