- Programing </br>
  -> 프로그래밍이란 컴파일러를 통해 인간의 언어인 자연어를 컴퓨터의 언어인 기계어로 바꾸어 줌으로써 컴퓨터에게 명령을 내리는 행위이다.</br>
  -> 프로그래밍에는 변수를 통해 값을 할당하고 연산자를 이용해 연산을 하며 if문,for문등을 통해 흐름을 제어하며 함수를 통해 재사용이 가능한 구문의 집합을 만들고 객체와 배열을 이용하여 자료구조를 만든다.</br>
- ES5</br>

- 함수</br>
-> 함수란 어떤 특정 작업을 수행하기 위해 필요한 일련의 구문들을 그룹화하기 위한 개념</br>
-> 만일 동일한 작업을 반복적으로 수행해야 한다면 미리 작성된 함수를 재사용할 수 있다(코드의 재사용)</br>
-> 함수의 기능은 특정 작업을 수행하는 구문들의 집합을 정의하고 필요시에 호출하여 필요한 값 또는 수행 결과를 얻는 것.</br>

- Statement (구문)</br>
-> 구문이란 컴퓨터에 의해 실행될 명령들의 집합이다</br>
-> 구문은 값,연산자,키워드,조건문,표현식,주석으로 이루어져있다.</br>
-> 함께 실행이 되어져야 할 구문은 코드블럭으로 구분할 수 있다.</br>

- Expression (표현식)</br>
-> 표현식은 변수와 연산자 그리고 값으로 이루어져 있으며 하나의 값을 가질 수 있다</br>
-> 즉 표현식은 하나의 값으로 수렴한다</br>
-> 표현식은 구문이 될 수 있지만 구문은 표현식이 될 수 없다. </br>

- Framework VS Library</br>
-> Library는 객체지향 프로그래밍에서 미리 만들어진 코드들의 컬렉션(?)이라 할 수 있다. 미리 만든 함수들을 라이브러리에 저장해 놓고,        개발자들은 필요시 가져와 편리하게 사용할 수 있는 곳이다.</br>
   Framework는 Library와 달리 어플리케이션의 틀과 구조를 결정할 뿐 아니라, 그 위에 개발된 개발자의 코드를 제어한다. 프레임워크는 구체적이며 확장 가능한 기반 코드를 가지고 있으며, 설계자가 의도하는 여러 디자인 패턴의 집합으로 구성되어 있다.</br> 


- Operator</br>
-> 연산자로써 좌항과 우항의 값을 이용해 연산을한다.</br>

- Control flow</br>
-> 객체지향 언어들은 절차지향과 다르게 if문과 for문을 사용하여 흐름을 제어가능하다</br>

- Code block (Block statement)</br>
-> 블록 구문은 구문들의 집합으로 중괄호로 그 범위를 정한다</br>
-> 일반적으로 함수, 객체리터럴, 흐름제어구문에서 사용된다.</br> 

- Pass-by-value VS Pass-by-reference</br>
  
- Pass-by-reference</br>
 : 객체형 또는 참조형이라고 한다
   객체는 메모리에 저장할 수 있는 값이 가변적이다. 그러므로 메모리의 힙 부분에 저장이 된다.</br>
   만일 새로운 값을 할당 받았을 경우 스택에 힙 영역을 가리키는 주소값이 달라진다. </br>
   참조에 의한 방식은 실제 원본의 참조와 비교를 통해 이루어진다 즉, 원본에 영향을 미친다.</br>


- Pass-by-value</br>
: 기본자료형은 메모리에 저장할 수 있는 값은 고정되어있다. 그러므로 메모리의 스택부분에 저장이 된다.</br>
  만일 새로운 값을 할당을 받았을 경우 고정된 메모리 영역을 점유하고 다른곳에 값을 저장한다. </br>
  기본자료형의 값은 값(value)로 저장된다. 즉 값이 복사되어 전달되기 때문에 원본에 영향을 미치지 않는다.</br> 

- Object의 property VS method</br>
-> 객체(Object)는 이름과 값으로 이루어진 property와 동작을 의미하는 method로 이루어진다.</br>
   method 역시 property와 같이 함수가 될 수 있으므로 이를 구분해 주기 위해 method라는 이름을 붙였다.</br>

- Hoisting (변수 hoisting vs 함수 hoisting)</br>
-> 호이스팅(Hoisting)이란 모든 선언문이 스코프의 선두로 옮겨진것처럼 동작하는 특성을 말하는 것이다. 
   변수 hoisting은 선언과 초기화가 한번에 이루어지고 undefined로 초기화된다 값의 할당은 할당문에서 나중에 따로 이루어 진다. 
   하지만 함수 hoisting은 선언과 초기화 그리고 값의 할당이 한번에 이루어 진다. 
   함수 표현식의 경우 함수 호이스팅이 아닌 변수 호이스팅이 발생한다. </br>

- 일급계체</br>
-> 생성,대입,연산,인자 또는 반환값으로서의 전달 등 프로그래밍 언어의 기본적 조작을 제한없이 사용할 수 있는 대상을 의미
   일급객체의 조건</br>
- 무명의 리터럴로 표현이 가능
- 변수나 자료구조(객체,배열...)에 저장가능
- 함수의 파라미터로 전달가능
- 반환값으로 사용가능 

- Call-by-value VS Call-by-reference 

 - Call-by-value</br>
 -> 기본자료형 인수는 값에 의한 호출로 동작한다.</br>
 -> 기본자료형의 인수를 함수의 매개변수에 전달할 때 매개변수에 있는 값을 복사하여 함수로 전달되는 방식</br>
 -> 이때 함수내에서 매개변수를 통해 기본자료형이 변경되더라도 전달이 완료된 기본자료형의 값은 변경되지 않는다. </br>
 
 - Call-by-reference</br>
 -> 객체형 인수는 참조에 의한 호출로 동작한다.</br>
 -> 객체형의 인수를 함수의 매개변수에 전달할 때 객체의 참조값이 매개변수에 저장되어 함수로 전달되는 방식</br>
 -> 참조에 의한 호출로 매개값이 변경되었을 때 전달되어진 참조형의 인수값도 같이 변경이 된다. </br>

- prototype 객체 </br>
-> 모든 객체는 자신의 부모역할을 하는 prototype 객체와 연결되어있다.</br>
-> prototype 객체는 생성자 함수에 의해서 생성이 된 각각의 객체에 공유 프로퍼티를 제공하기 위해 사용한다.</br>
-> 자바스크립트의 모든 객체는 자신의 프로토타입을 가리키는 [[Prototype]]이라는 숨겨진 프로퍼티를 갖는다.</br>
-> 결정된 프로토타입의 객체는 다른 임의의 객체로 변경 가능하다  </br>

- [[Prototype]] 프로퍼티 vs prototype 프로퍼티 </br>
 
- __proto__프로퍼티(=[[Prototype]])</br>
-> ECMAScript spec에서 모든 객체는 자신의 프로토타입을 가리키는 [[Prototype]]이라는 숨겨진 프로퍼티를 가진다.</br> 
-> 함수의 프로토타입 객체는 Function.prototype이며 이것 역시 함수이다. </br>

- prototype 프로퍼티</br>
-> 함수 객체만 가지고 있는 프로퍼티</br>
-> 함수 객체가 생성자로 사용될 때 이 함수를 통해 생성된 객체의 부모 역할을 하는 객체를 가리킨다.</br>
-> 함수가 생성될 때 만들어 지며 constructor 프로퍼티를 가지는 객체를 가리킨다. 이 constructor 프로퍼티는 함수 객체 자신을 가리킨다.</br> 
-> [[Prototype]] 프로퍼티는 함수 객체의 부모 객체(Function.prototype)를 가리키며 prototype 프로퍼티는 함수객체가 생성자 함수로 사용되어 객체를 생성할 때 생성된 객체의 부모 객체 역할을 하는 객체를 가리킨다.</br> 

- constructor 프로퍼티</br>
-> 프로토타입 객체는 constructor 프로퍼티를 갖는다. 이것은 객체의 입장에서 자신을 생성한 객체를 가리킨다. </br>

- navtive object VS Host object </br>

 - native object</br>
 -> ECMAScript 명세에 정의된 객체</br>
 -> 애플리케이션 전역의 공통 기능을 제공</br>
 -> 애플리케이션의 환경과 관계없이 언제나 사용가능</br>

 - Host object(=Global Object)</br>
 -> 브라우저 환경에서 제공하는 window,HTMLElement등의 DOM 노드 객체와 같이 호스트 환경에 정의된 객체</br>
 -> ECMAScript 환경에서의 실행의 완성을 위해 호스트 환경에서 제공하는 객체</br>

 * 함수의 프로퍼티</br>
- arguments 프로퍼티</br>
-> arguments 객체는 함수 호출 시 전달된 인수들의 정보를 담고 있는 순회가능한 유사 배열 객체이다. </br>
-> 함수 객체의 arguments 프로퍼티는 arguments 객체를 값으로 가지며 함수 내부에서 지역변수처럼 사용됨. 외부에서는 사용불가 </br>
-> arguments 객체는 매개변수 갯수가 확정되지 않은 가변 인자 함수를 구현할 때 유용하게 사용된다. </br>

- caller 프로퍼티</br>
-> caller 프로퍼티는 자신을 호출한 함수를 의미한다</br>

- length 프로퍼티</br>
-> length 프로퍼티는 함수 정의 시 작성된 매개변수 갯수를 의미 </br>

- name 프로퍼티</br>
-> 함수명을 나타냄, 기명함수의 경우 함수명을 값으로 갖고 익명함수의 경우 빈문자열을 값으로 갖는다.</br>

- __proto__프로퍼티(=[[Prototype]])</br>
-> ECMAScript spec에서 모든 객체는 자신의 프로토타입을 가기키는 [[Prototype]]이라는 숨겨진 프로퍼티를 가진다. </br>
-> 함수의 프로토타입 객체는 Function.prototype이며 이것 역시 함수이다. </br>

- prototype 프로퍼티</br>
-> 함수 객체만이 가지고있는 프로퍼티이며 자스 객체지향의 근간</br>
-> prototype프로퍼티와  [[Prototype]] 프로퍼티는 모두 프로토타입 객체를 가리키지만 관점의 차이가 있다.</br>
