VELOPERT.LOG 님의 글을 읽고 따라해가며 만들었습니다.
https://velopert.com/3533


## 템플릿에 이미 이뤄진 작업:

### 0. 절대경로에서 파일을 불러 올 수 있도록 설정

- .env: NODE_PATH 설정
- jsconfig.json: 에디터 설정
- package.json : NODE_PATH 설정 적용

### 1. 패키지 설치
```bash
$ yarn add redux react-redux redux-actions immutable
```

### 2. 불필요한 파일 제거
- App.js
- App.css
- App.test.js
- logo.svg

### 3. 주요 컴포넌트 생성 및 루트 컴포넌트 생성

- components/
  - App.js
  - AppTemplate.js
  - Counter.js
  - Todos.js
- containers/
  - CounterContainer.js
  - TodosContainer.js
- Root.js

### 4. 리덕스 관련 코드를 작성 할 파일 생성
- store
  - modules
    - counter.js
    - todo.js
    - index.js
  - configure.js
  - index.js
  - actionCreators.js
