# design

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).


### props 선언 방법

1. 배열
props: ['title'],

2. 객체

props:{
        title: String,
    }

props validation 문법
type: Array, -> 무조건 배열로 들어와야한다 배열값이 아닌경우 에러가 뜸
required: true, -> 이값은 필수값이다라고 기본설정을 할수 있음

넘겨야하는 속성을 넘길 수 있음


### 부모로 바로 emit 사용

보통 메서드에 선언을해서 썻지만 v-on 클릭에 담아서 바로 올려보낼 수 있다.