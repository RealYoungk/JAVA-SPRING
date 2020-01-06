# Nodejs
## javascript
### javascript base
- 'use strict' : ES5부터 적용되는 코드, 안전한 코딩을 위한 Strict mode 선언 방식이다. 암시적 선언 변수 사용 불가, 읽기전용 변수에 값 할당 불가, 확장 할 수 없는 객체 확장 불가
- const obj = { title : 'aaa' }
- function f () { return true }   or    const f = () => obj.title? true : false

### Event Loop Data Structure
- Call Stack : 함수를 가장 먼저 들어온거부터 처리함
- Callback Queue : 사용자의 이벤트(클릭)(언제 들어올지 모름)를 Call Stack 이 비어있을때 이벤트 루프를 통해 밀어넣음
- Event Loop : 풀링
- web api : 화면상에 출력
