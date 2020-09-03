# 2주차

## 조건문

### 조건문 (if문, switch문)

* 단일 if문

```
if ( 조건식 ) {
      실행문:
}


int num = 0;
String Str = "";

if (num%2 == 0) {
	str = "짝수";
}

if (num%2 !=0) {
	str = "홀수";
}
``` 

*  if else 문

```
if ( 조건문 ) {
	실행문;
} else {
	실행문;
}


if (num%2 ==0) {
	str = "짝수";
} else {
	str = "홀수";
}
```

* else if문

```
 if ( 조건식 ) {
 	조건식;
 } else if ( 조건식 ) {
 	조건식;
 } else {
 	조건식
 }
 
 
 if ( num%3 == 0 && num%4 == 0) {
 	str = "3과 4의 배수 입니다.";
 } else if (num%4 == 0) {
 	str = "4의 배수 입니다.";
 } else if (num%3 == 0) {
 	str = "3의 배수 입니다,";
 } else {
 	str = "3과 4의 배수가 아닙니다.;
 }
 
```
