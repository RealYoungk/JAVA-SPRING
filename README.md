# JAVA-SPRING
자바, 스프링 공부
## JAVA
### Singleton pattern
- 하나만 존재해야하는 객체를 만들때 사용
- instance 를 저장할 static 변수 하나 선언
- new instance
- getInstance 로 객체 주소값 리턴
- 이러한 방식으로 객체를받는 예 -> 캘린더(날짜는 딱 하나만 존재해야함)


### Factory Method Pattern
- 객체간 연관성을 줄일려고 쓰는것 같음
- 아직 잘 모르겠음

### 상속
- A : 부모객체, B : 자식객체
- A 자료형 = new 자식객체 => 업캐스팅 가능
- 힙 메모리 구조는 부모객체 생성자가 먼저 호출되어 할당되고 자식객체 생성자가 호출되어 할당
- 업캐스팅하면 부모것만 쓸 수 있음
