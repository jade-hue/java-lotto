# 로또
로또 구입 금액을 입력하면 구입 금액에 해당하는 로또를 발급해야 한다.
로또 1장의 가격은 1000원이다.

### 기능 목록
- [0] 1000단위 입력값이 들어와야한다.
- [O] 구입금액 따른 로또 번호 생성
- [O] 로또 당첨 번호 확인
- [O] 당첨 통계 확인


# 프로그래밍 요구 사항
자바 코드 컨벤션을 지키면서 프로그래밍한다.
#기본적으로 Google Java Style Guide을 원칙으로 한다.
#단, 들여쓰기는 '2 spaces'가 아닌 '4 spaces'로 한다.
#indent(인덴트, 들여쓰기) depth를 2를 넘지 않도록 구현한다. 1까지만 허용한다.
#예를 들어 while문 안에 if문이 있으면 들여쓰기는 2이다.
#힌트: indent(인덴트, 들여쓰기) depth를 줄이는 좋은 방법은 함수(또는 메서드)를 분리하면 된다.
#3항 연산자를 쓰지 않는다.
#else 예약어를 쓰지 않는다.
#else 예약어를 쓰지 말라고 하니 switch/case로 구현하는 경우가 있는데 switch/case도 허용하지 않는다.
#힌트: if문에서 값을 반환하는 방식으로 구현하면 else 예약어를 사용하지 않아도 된다.


### 기능 목록
- [x] 
- [x] 
- [x] 
- [x] 
- [x] 
- [x] 
- [x] 
- [x] 

# 추가된 요구 사항
모든 기능을 TDD로 구현해 단위 테스트가 존재해야 한다. 단, UI(System.out, System.in) 로직은 제외
핵심 로직을 구현하는 코드와 UI를 담당하는 로직을 구분한다.
UI 로직을 InputView, ResultView와 같은 클래스를 추가해 분리한다.
함수(또는 메서드)의 길이가 10라인을 넘어가지 않도록 구현한다.
함수(또는 메서드)가 한 가지 일만 하도록 최대한 작게 만들어라.
배열 대신 컬렉션을 사용한다.
Java Enum을 적용한다.
모든 원시 값과 문자열을 포장한다
줄여 쓰지 않는다(축약 금지).
일급 컬렉션을 쓴다.

# 힌트
로또 자동 생성은 Collections.shuffle()를 활용한다.
Collections.sort()를 활용해 정렬 가능하다.
ArrayList의 contains()를 활용하면 어떤 값이 존재하는지 유무를 판단할 수 있다.