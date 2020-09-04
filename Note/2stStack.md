#2주차
## 메모리 사용 내역
### Stack

* Heap 영역에 생성된 Object타입의 데이터의 참조값이 할당된다.
* 원신타입의 데이터가 값과 함께 할당된다.
* 지역 변수들은 scope에 따른 visibility를 가진다.
* 각 Thread 는 자신만의 Stack을 가진다.

Stack에는 Heap영역에 생성된 Object 타입의 데이터들에 대한 참조를 위한 값들이 할당된다.  
또한, 원시타입(primitive types) - byte, short, int, long, double, float, boolean, char 타입의 데이터들이 할당 된다.   
이때 원시타입의 데이터들에 대해서는 참조값을 저장하는 것이 아니라 실제 값을 Stack에 직접 저장하게 된다.


Stack영역에 있는 변수들은 visibility를 가진다.  
전역변수가 아닌 지역 변수가 함수내에서 Stack에 할당 된 경우, 해당 지역 변수는 다른 함수에서 접근할 수 없다.  
중괄호 }가 실행된 경우(함수가 종료된 경우), 함수 내부에서 선언한 모든 지역 변수들은 Stack에서 pop되어 사라진다.  

Stack 메모리는 Thread 하나당 하나씩 할당된다.
Thread 하나가 새롭게 생성되는 순간 해당 Thread를 위한 Stack도 함께 생성되며, 각 Thread에서 다른 Thread의 Stack영역에는 접근할 수 없다.

[링크](yaboong,github,io/java/2018/05/26/java-memory-management/)