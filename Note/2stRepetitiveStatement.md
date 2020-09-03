# 2주차
## 반복문
### 반복문 (for문, while문, do~while문)

* for문

```
for ( 조건; 최대값; 증가값)

int dan;

for (int i =1; i <= 9; i++) {       // i++    =     i = i +1
	
	System.out.println(dan + " * " + i + " = " +  (dan*i));
	System.out.printf("%d * %d = %d\n", dan, i, (dan * i));
	
}
```

* while문

```

int j = 1;    // 초기값

while (j <= 9) {

	System.out.printf("%d * %d = %d\n", dna, j, (dan * j));
	
	j++;
	
}
```

* do~while (최대값)

```
int k = 0;

do {

	k++;
	System.out.printf("%d * %d = %d\n", dan, k, (dan * k));
	
} while(k < 9);
```				

