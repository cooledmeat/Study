# 1주차

* 클래스의 이름의 첫 글자는 반드시 대문자
* 파일의 이름은 클래스의 이름과 동일
	* main method
	* method 이름은 반드시 소문자로 시작
	* public = 접근지정자
	* property - void = {} 사이값을 되돌리지 않는다.
	* String[] args - main method에 꼭 가지고 와야할 것. [매개변수, 인수]
	
	```
	import java.io.*;   // io에 있는 모든 클래스를 메모리에 할당시킨다.
	import java.io.BufferedReader;
									// 예외처리 (try catch)
	public static void main(String[] args) throws IOException{   // argument = 요소
		System.out.println("자바 첫 시간");  // ln = \n - 줄바꿈 (정규화 표현식)
		System.out.print("오늘은 목요일!\n");
		System.out.println();
	```
	* import java.io : 클래스가 있는 위치(package) - 해당 메소드를 사용할때 추가 해줘야 한다. 라이브러리 쓸때랑 비슷한거 같다.
	* BufferedReader : 메모리상에 저장공간을 만들어 처리속도를 높임
	* System.in : 키보드를 통한 1byte를 입력 받음. 문자로 바꿔서 한 문자씩 읽는다.
	* inputStreamReader : 입력받은 1byte를 문자(2byte)로 변환

	
	```
	int r;
	double area, len;
	
	r = Integer.parseInt(br.readLine());  // readerLine - 문자로 읽음. integer - 정수 변환
	
	System.out.println("반지름" + r);
	System.out.println("넓이" + area);
	System.out.println("둘레" + len);
	
	```
	
* 코딩 오류 - 컴파일 오류
* 실행시 오류 - 런타임 오류 (값을 받아오면서)
* 인터프리터 언어 - 코드 줄 순서대로 읽는다.
* 컴파일 언어 - 기계어로 바꿔서 한번에 읽는다.
	