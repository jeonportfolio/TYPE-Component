## 프로젝트 생성 
`npx create-expo-app -t expo-template-blank-typescript`<br>
기존 javascript로 구성한 컴포넌트를 typescript로 변환한다.(js파일을 모두 tsx파일로 변환)<br>

## typescript 테스트 

json의 scripts에 test:typescript:"tsc"추가  ->`npm run test:typescript`실행<br>

## 아이콘 설치

` npm install @expo/vector-icons `<br>

## TypeScript변환 

children들은 reactElement로 받아준다.
TypoGraphy를 import 하기위해 count의 유무를 판별하여 prop으로 받아준다.
