## Vue LifeCycle

![스크린샷 2022-05-11 오후 1.24.53](/Users/mac/Library/Application Support/typora-user-images/스크린샷 2022-05-11 오후 1.24.53.png)

[출처: https://kr.vuejs.org/v2/guide/instance.html#%EB%9D%BC%EC%9D%B4%ED%94%84%EC%82%AC%EC%9D%B4%ED%81%B4-%EB%8B%A4%EC%9D%B4%EC%96%B4%EA%B7%B8%EB%9E%A8]

### LifeCycle 순서

beforeCreate -> created -> beforeMount -> mounted -> (Data 업데이트시) (beforeUpdate -> updated) -> beforeDestroy -> destroyed

- Data를 바인딩하거나 웹 페이지에 보여줄 때 beforeCreate나 created에 넣어주어 mount 되기 전에 데이터 세팅시켜 보여주도록 처리해준다.
- Created: mount 되기전 상태
- Mount: 화면상에 컴포넌트가 보여지는 것
- Update: data가 업데이트 되면 호출 되는 것



### watch

- watch는 data명으로 메소드 형식으로 만들어주어 data가 변경될 시 관찰할 수 있는 기능

  -> console창에 데이터의 변경사항을 찍어주는 것



