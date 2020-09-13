# ifl-vue-trello

## 1. 코드 스캐폴딩

### vue-cli 설치

```
$ npm i -g vue-cli
```

```
$ vue init webpack-simple
```

설정 완료.

## 2. 라우팅

서버 라우팅, 브라우저 라우팅이 있다.

서버 라우팅은 주소를 요청할 때마다 화면이 갱신된다.

브라우저 라우팅은 화면이 갱신되지 않고 화면이 변경되는 요소들만 변경된다.

브라우저 라우팅의 장점은 서버 라우팅에 비해 빠른 화면 변환이 이루어진다.

데이터는 백엔드 API로부터 받아와서 화면을 바꾼다.

### 2-1 라우터 직접 만들기

뷰 어플리케이션이 동작할 때 가장 먼저 작동하는 파일은 main.js다. 

## 중첩 라우트

computed

## SPA

SPA 는 서버 API에서 받아온다.

## axios wrapping 해서 사용하기

## mutation은 동기적, action 은 비동기

변이는 무조건 동기. 비동기 처리는 action으로 처리한다.

action은 변이와 유사하지만 상태를 변이시키지 않는다.

action은 mutation을 실행시켜서 state를 변화시킨다.

# dragula

드래그 앤 드랍을 위한 라이브러리