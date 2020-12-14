# NestJS Study Project

- Main의 bootstrap 함수 명은 아무거나 지어도 됨
- 첫번째 App.module.ts로 들어가보기
- 데코레이터는 클래스에 함수 기능을 추가할 수 있음
  - 클래스 위의 함수

- 모듈 - 컨트롤러 (get) - 서비스 (injectable)

- 모든 프로젝트는 main.ts에서 시작함
- 모듈은 앱의 일부
- 인증 담당 앱 유저 모듈
- 인스타그램 포토 모듈, 비디오 모듈 등...

- 컨트롤러 : url을 가져와서 함수를 실행함 (라우터 url과 함수 매핑)
- get == get 라우터

- 데코레이터는 반드시 함수와 붙어있어야 함
- 익스프레스와 다른 점은 get 함수 대신 데코레이터를 사용하낟
- 404 같은 것을 다 자동으로 해줌...  


## 왜 서비스가 필요한가?
- netsjs 는 mvc 모델
  - 컨트롤러와 서비스의 분리
  - 콘트롤러와 비즈니스 로직의 분리
  - 컨트롤러는 단지 url을 가져온다
  - 비즈니스 로직은 서비스로 간다

- AppModule은 루트 모듈 
- 모든게 AppModule 안에 들어가야 함

- /:id 시 param(id)이름은 같아야함
  - 변수는 달라도 됨

- class-validator
- class-transformer

