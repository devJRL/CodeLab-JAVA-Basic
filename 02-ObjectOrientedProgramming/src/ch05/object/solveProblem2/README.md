### :open_book:

[Go Home](https://github.com/devJRL/CodeLab-JAVA-Basic#codelab-java-basic) / [Go Up](..#ch05객체)

# 문제 풀기 2

## 문제1

- [날짜 유효성 검증 프로그램 구현](./MyDate.java#L6)

```
	- day, month, year 변수는 private로 작성합니다.
	- 각 변수의 getter,setter를 public으로 작성합니다.
	- MyDate(int day, int month, int year) 생성자를 작성합니다.
	- public boolean inValid() 메서드를 만들어서 날짜가 유효한지 확인합니다.
	- 율리우스력을 기준으로 4년마다 윤달이 돌아오도록 체크합니다.
	- [MyDateTest 클래스](./MyDateTest.java)에서 생성한 MyDate 날짜가 유효한지 확인합니다.
```

- [출력결과](./MyDateTest.java#L6)

```
	검증 연 : 2019
	검증 월 : 10
	검증 일 : 31
	검증 결과, 위 날짜는 유효합니다.
	
	----------------------------------
	
	검증 연 : 2019
	검증 월 : 2
	검증 일 : 29
	검증 결과, 위 날짜는 유효하지 않습니다.
```

<br/><div align="right"><b><a href="#open_book">↥ back to top</a></b></div><br/>

## 문제2

- [커피값 계산 후 잔액 확인 프로그램 구현](./Buyier.java#L6)

```
	- 김 졸려 씨는 10,000짜리 현찰을 가지고 있었습니다.
	- 김 졸려 씨는 4,000원을 내고 별다방에서 [아메리카노를 사 마셨습니다.](./Buy.java)
	- 이 피곤 씨는 김졸려씨에게 5,000원 짜리 지폐를 빌렸습니다.
	- 이 피곤 씨는 4,500원을 내고 [라떼를 사마셨습니다.](./Buy.java)
	- 두 사람의 각각 잔액은 얼마인지 [구현](./BuyCoffeeTest.java)해 봅시다. 
```

- [출력결과](./BuyCoffeeTest.java#L3)

```
	김 졸려님의 잔고 : 10000
	김 졸려님이 별다방에서 아이스 아메리카노를 사마셨습니다.
	김 졸려님의 잔고 : 5900
	김 졸려님이 이 졸려에게 5000원을 빌려 줌
	김 졸려님의 잔고 : 900
	이 졸려님의 잔고 : 5000
	이 졸려님이 별다방에서 아이스 아메리카노를 사마셨습니다.
	이 졸려님의 잔고 : 400
```

<br/><div align="right"><b><a href="#open_book">↥ back to top</a></b></div><br/>
