# javascript-racingcar-precourse

## 구현할 기능 목록

### input
- [x] 자동차 이름을 입력받는다.
- [x] 시도 횟수를 입력받는다.

### output
- [x] 각 차수 별 실행 결과를 출력한다.
- [x] 최종 우승자를 출력한다.

### game
- [x] 이름을 쉼표(,)로 구분한다.
- [x] 0~9 사이의 무작위 값을 구한다.
- [x] 무작위 값이 4 이상인 경우 전진한다.
- [ ] 사용자가 잘못된 값을 입력할 경우 [ERROR]로 시작하는 메세지와 함께 Error를 발생시킨 후 애플리케이션을 종료한다.

### validate
- [x] 공백을 입력하면 에러를 발생시킨다.
- [x] 자동차 이름 구분자가 존재하지 않으면 에러를 발생시킨다.
- [x] 시도 횟수는 0 이상 숫자여야 한다.

```
경주할 자동차 이름을 입력하세요.(이름은 쉼표(,) 기준으로 구분)
pobi,woni,jun
시도할 횟수는 몇 회인가요?
5

실행 결과
pobi : -
woni :
jun : -

pobi : --
woni : -
jun : --

pobi : ---
woni : --
jun : ---

pobi : ----
woni : ---
jun : ----

pobi : -----
woni : ----
jun : -----

최종 우승자 : pobi, jun
```