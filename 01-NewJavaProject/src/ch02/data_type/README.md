### :open_book:

[Go Home](https://github.com/devJRL/CodeLab-JAVA-Basic#codelab-java-basic) / [Go Up](../..#자바-입문)

# Ch02. 기초 자료구조

## 원시형 자료구조

### [정수형](./Basic1_Integer.java)

> **byte**  
> - 크기 : 1 byte = 8 bit  
> - 범위 : 8비트 자리중 최상위 자리는 부호비트로 제외, -2^7 ~ 2^7-1 의 범위를 표현

> **short**  
> - 크기 : 2 byte = 16 bit  
> - 범위 : 16비트 자리중 최상위 자리는 부호비트로 제외, -2^15 ~ 2^15-1 의 범위를 표현
 
> **int** (가장 많이 사용하는 정수자료)  
> - 크기 : 4 byte = 32 bit  
> - 범위 : 32비트 자리중 최상위 자리는 부호비트로 제외, -2^31 ~ 2^31-1 의 범위를 표현  

> **long** (4바이트를 초과하는 정수를 저장하는 자료형)  
> - 크기 : 8 byte = 64 bit  
> - 범위 : 64비트 자리중 최상위 자리는 부호비트로 제외, -2^63 ~ 2^63-1 의 범위를 표현

```java
	byte b = -128;
	short s = -32768;
	int i = -2147483648; // 21억 4748만 3648
	long l = -9223372036854775808L; // 922경 3372조 386억 5477만 5808
```

<br/><div align="right"><b><a href="#open_book">↥ back to top</a></b></div><br/>

### [문자형](./Basic2_Character.java)

> **char**  
> - 크기 : 2byte
> - 문자 세트(Character set)를 인코딩(Encoding)하여 문자를 위한 코드값(숫자값)으로 전환  
> - 코드값을 문자 세트로 되돌리려면 디코딩(Decoding)으로 전환    
> - 자바는 기본적으로 Unicode를 사용하고, UTF-8을 기본으로 사용

<br/><div align="right"><b><a href="#open_book">↥ back to top</a></b></div><br/>

### [실수형](./Basic3_Floats.java)

> **double** (실수형 기본 자료형)
> - 크기 : 8 byte

> **float**
> - 크기 :  4 byte
> - 기본 자료형인 double은 float보다 큰 자료형이므로  
> 식별자(f)를 붙여서 작은 자료형(float타입)으로 명시해줌


> **부동소수점 방식**
? - 실수를 십진수로 지수부와 가수부로 표현  
> - 0.1 -> 1.0 x 10 ^ -1    
> - float (32bit) - 부호비트[1], 지수비트[8], 가수비트[23]  
> - double(64bit) - 부호비트[1], 지수비트[11],가수비트[52]

> 아주 넓은 범위의 실수릂 표현할 수 있는 장점  
> 0을 표현할 수 없음으로 인해서 오차가 발생할 수 있음

<br/><div align="right"><b><a href="#open_book">↥ back to top</a></b></div><br/>

### [논리형](./Basic4_Boolean.java)

> **boolean**
> - 크기 : 1byte
> - 참(true) 또는 거짓(false)을 저장하기 위한 논리 자료형 (기본값은 false)

<br/><div align="right"><b><a href="#open_book">↥ back to top</a></b></div><br/>

## 자료의 상태

### [상수와 리터럴](./Constant_and_Literal.java)

- **상수(constant)** : 변하지 않고 고정된 값  
- **리터럴(literal)**  : 프로그램에서 사용하는 모든 값 (숫자값, 문자갑, 논리값)  

> 모든 리터럴은 상수 풀(constant pool)에 저장.  
> 상수풀에 저장될 때, 정수는 int, 실수는 double로 저장.

<br/><div align="right"><b><a href="#open_book">↥ back to top</a></b></div><br/>

### [형 변환](./Type_Casting.java)

- **형 변환** : 서로 다른 자료형의 값이 대입되는 경우 형을 변환하여 자료형을 맞추는 것

> 1. 묵시적 형 변환(자동, implict type conversion)  
> : 작은 수에서 큰 수로, 덜 정밀한 수에서 더 정밀한 수로 대입되는 경우  
>  
> 2. 명시적 형 변환(수동, explict type conversion)  
> : 변환되는 자료형을 명시하여 저장하는 경우. 자료의 손실 발생 가능성이 있음

  
- **형 변환 관계** : small -> big

> 1. byte(1 byte) -> short(2 byte) -> int(4 byte) -> long(8 byte)
> 2. char(2 byte) -> int(4 byte) -> long(8 byte)
> 3. 정수 -> 실수
> 4. float(4 byte) -> double(8 byte)

<br/><div align="right"><b><a href="#open_book">↥ back to top</a></b></div><br/>
