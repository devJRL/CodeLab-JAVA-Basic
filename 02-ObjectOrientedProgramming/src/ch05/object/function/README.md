### :open_book:

[Go Home](https://github.com/devJRL/CodeLab-JAVA-Basic#codelab-java-basic) / [Go Up](..#ch05객체)

# 객체, 함수, 메모리 그리고 생성자

## [함수(function)](./FunctionTest.java#L3)

- 하나의 기능을 수행하는 일련의 코드를 의미합니다.
- 함수는 호출하여 사용하고, 기능이 수핸된 후 값을 반환할 수 있습니다.
- 함수로 구현된 기능은 여러 곳에서 호출되어 사용될 수 있습니다.

<br/><div align="right"><b><a href="#open_book">↥ back to top</a></b></div><br/>

## 객체, 클래스, 함수, 변수 그리고 메모리

> **object** (객체)  
> 객체 지향 프로그램의 대상, 생성된 인스턴스

> **class** (클래스)  
> 객체를 프로그래밍하기 위해 코드로 만든 상태 

> **member variable** (멤버변수, 전역변수)  
> 클래스 내부에 생성된 변수

> **new**  
> 클래스를 객체(object)로 생성하기 위해 사용하는 예약어  
> 생성된 객체는 `heap메모리`를 점유

> **instance** (인스턴스)  
> 클래스로부터 생성된 객체(object), 즉 클래스가 메모리에 생성된 상태

> **reference variable** (참조변수)  
> 메모리에 생성된 인스턴스를 가리키는 변수

> **reference value** (참조 값)  
> JVM에 의해 생성된 인스턴스의 메모리 주소 값  

<br/><div align="right"><b><a href="#open_book">↥ back to top</a></b></div><br/>

> **method** (메서드)  
> 멤버 변수를 이용하여 클래스의 기능 구현된 코드 (호출되어 수행)  
> 함수의 일종으로 입력인자를 받아서 수행 후 지정된 결과를 반환하는 수행문 단위

> **parameter** (파라미터, 매개변수, 입력인자)  
> 함수가 입력받는 값  

> **return**  
> 함수가 수행 후 돌려주는 결과값

> **local variable** (지역변수)  
> 메소드 내부 혹은 braket({,})내부 에서 생성된 변수 

<br/><div align="right"><b><a href="#open_book">↥ back to top</a></b></div><br/>

> **heap memory** (힙 메모리)  
> 인스턴스가 생성시 점유하는 영역. 멤버 변수의 크기에 따라 점유하는 **동적 메모리**  

> **stack memory** (스택 메모리)  
> 함수가 호출되는 순서대로 쌓여서 수행 후 완료되면 사라지는 메모리  
> 인스턴스가 생성되고 나면 **힙 메모리**를 참조하는 메모리를 점유  

<br/><div align="right"><b><a href="#open_book">↥ back to top</a></b></div><br/>

## [생성자(constructor)](./Constructor.java#L6)

- 클래스를 인스턴스로 생성될 때 수행할 구문을 정의하는 함수
- 리턴을 명시하지 않고 만드는 파라미터에 따라 다양하게 정의 생성자 (생성자 오버로딩)

<br/><div align="right"><b><a href="#open_book">↥ back to top</a></b></div><br/>
