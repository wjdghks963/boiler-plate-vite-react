# React Vite RTK

Basic Setup boilerplate

## Motivation

Vanilla React 사용할 때 반복되는 설정을 줄이기 위해 모든 세팅 / 구조 포함한 프로젝트

**번들러 Vite 컴파일러 SWC**사용한다.

### TODO

시작 전 반드시 해야할 것

- [ ] index.html title, head svg 는 꼭 바궈야 한다.
- [ ] Proxy Server가 필요한 경우 [이것](https://ko.vitejs.dev/config/server-options.html#server-proxy)을 읽어야한다

<hr/>

## Style

스타일 라이브러리는 상황에 맞게 사용함

Admin : [Antd](https://ant.design/)

Provide Functional Components :

[MUI](https://mui.com/material-ui/getting-started/installation/)

[Chakra UI](https://chakra-ui.com/getting-started)

Custom : [Tailwindcss](https://tailwindcss.com/docs/installation)

Interaction Custom : [Styled-Components](https://styled-components.com/)

<hr/>

## 실행 방법

1. npm i
2. npm run dev

## Template에서 추가된 패키지 & 파일

1. .prettierrc

>    [prettier playground](https://prettier.io/playground/)

2. TS Path Alias

>    Example -> tsconfig.json 내의 Path Alias Example 참조

3. Global Types

>    전역 타입 설정은 vite-env.d.ts 에서 한다

4. 폴더 구조

>    page(페이지), component(컴포넌트), utils(유틸리티), store(상태관리)

5. [Router dom (Browser Router)](https://reactrouter.com/en/main/routers/create-browser-router)

>    main.tsx 라우터(rouet.tsx) 적용

6. 상태관리

>    Redux Tool Kit을 사용하고 logger 포함시킴
