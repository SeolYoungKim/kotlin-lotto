# kotlin-lotto
## 2단계 - 로또(자동)
### 기능 요구사항
- 로또 구입 금액을 입력하면 구입 금액에 해당하는 로또를 발급해야 한다.
- 로또 1장의 가격은 1000원이다.

### 기능 목록 
- 입력 
  - [x] 구입 금액 입력
  - [x] 당첨 번호 입력 
- 출력
  - [x] 구입 금액 입력 안내 메세지 
  - [x] "N개를 구매했습니다" 라는 메세지 
  - [x] 구매한 로또들의 번호 목록 
  - [x] 당첨 번호 입력 안내 메세지 
  - [x] 당첨 통계 
    - [x] 수익률은 소수점 아래 3자리까지만 나타낸다  
- 로또 게임 
  - [x] 입력된 금액에 따라 로또를 구매한다 
    - [x] 천원 단위가 아니면 예외를 발생
    - [x] 로또는 1~45 랜덤 숫자 6개로 이루어져 있어야 한다
  - [x] 입력된 당첨 번호를 저장한다
- 로또 제약조건
  - [x] 숫자는 반드시 6개여야 한다
  - [x] 숫자는 1~45까지의 숫자여야 한다
- 구매한 로또와 당첨 번호 비교
  - [x] 구매한 로또 목록과 당첨 번호를 비교한다
  - [x] 등수 별로 개수를 기록한다
- 로또 통계 
  - [x] 구매한 금액 대비 당첨 금액으로 수익률을 계산한다 