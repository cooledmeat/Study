#2주차
## 배열
* 같은 타입의 데이터를 연속된 공간에 나열시키고, 각 데이터에 인덱스(Index)를 부여해 놓은 자료구조.
* 배열은 같은 타입의 데이터만 저장할 수 있다.
* 배열의 선언과 동시에 저장할 수 있는 데이터 타입이 결정
* 한번 생성된 배열의 길이는 변경 불가


##### 배열 선언

```
배열의 선언

타입[] 변수;                              타입 변수[];

int[] intArray;                          int intArray[];
double[] doubleArray;            double double[];
```


* 배열 변수는 참조 변수에 속한다.
* 배열도 객체이므로 힙 영역에 생성되고 배열 변수는 힙 영역의 배열 객체를 참조
* 참조할 배열 객체가 없다면 배열 변수는 null 값으로 초기화 될 수 있다.


##### 값 목록으로 배열 생성
* 배열 항목에 저장될 값의 목록이 있을 경우

```
데이터타입[] 변수 = {값1, 값2, 값3, .... };

```

###### new 연산자로 배열 생성
* 값의 목록을 가지고 있지 않지만 향후 값들을  저장할 배열을 미리 만들어야 할 경우 new연산자로 배열 객체를 생성

```
타입[] 변수 = new 타입[길이];

```

* new 연산자로 배열을 생성할 경우에는 이미 배열변수가 선언된 후에도 가능

```
타입[] 변수 = null;
변수 = new 타입[길이];
```

##### 배열 길이
* 배열의 길이란 배열에 저장할 수 있는 전체 항목 수를 말한다.
* 배열의 길이를 얻으려면 배열 객체의 length 필드를 읽으면 된다

```
배열변수.length

int[] intArray = {10, 20, 30,};
int num = intArray.length;
```