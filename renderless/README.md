# renderless

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


### renderless
스크립트만 제공하는 컴포넌트


### render()

render() 는 컴포넌트를 그리는것 어떤 컴포넌트의 표현
데이터만 예) 리스폰스 로딩등을 받아온다음에 정의했던 데이터만 노출하는것
컴포넌트를 등록한곳에 노출

$scopedSlots

하위컴포넌트에 데이터 등록한 하위컴포넌트 아래에서들고있엇던 데이터에 접근가능
