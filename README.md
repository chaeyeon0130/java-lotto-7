# java-lotto-precourse

## 💡 기능 구현 목록
### 1. 구입 금액 입력 및 검증
1-1. 로또 구입 금액 입력 받기
- [ ] 사용자가 로또 구입을 위해 금액을 입력하도록 합니다.
- [ ] 입력된 금액은 1000원 단위로 로또 개수를 계산합니다.

1-2. 구입 금액 검증
- 예외 상황에서 오류 메시지를 출력하고 사용자에게 금액을 재입력 받습니다.
  - 예외 상황
  - [ ] 금액이 숫자 형식이 아닌 경우
  - [ ] 금액이 1000원 단위가 아닌 경우

### 2. 로또 번호 자동 생성 및 검증
2-1. 로또 번호 자동 생성
- [ ] 사용자가 입력한 구입 금액에 따라, 구매할 로또 개수만큼 번호를 자동 생성합니다.

2-2. 로또 번호 검증
- 예외 상황에서 `IllegalArgumentException`을 발생시킨다.
  - 예외 상황
  - [ ] 각 로또 번호가 숫자 6개가 아닌 경우
  - [ ] 각 로또 번호가 1~45 사이의 숫자가 아닌 경우

### 3. 로또 번호 출력
3-1. 구입한 로또 번호 출력
- [ ] 생성된 모든 로또 번호를 사용자에게 출력합니다.

### 4. 당첨 번호 입력
4-1. 당첨 번호 입력 받기
- [ ] 사용자가 1~45 범위 내 숫자 6개를 입력하여 당첨 번호를 설정합니다.

4-2. 당첨 번호 검증
- 예외 상황에서 오류 메시지를 출력하고 사용자에게 당첨 번호를 재입력 받습니다.
  - 예외 상황
  - [ ] 숫자 형식이 아닌 입력이 포함된 경우
  - [ ] 1~45 범위를 벗어난 숫자가 포함된 경우
  - [ ] 번호 개수가 6개가 아닌 경우
  - [ ] 중복된 번호가 포함된 경우

### 5. 보너스 번호 입력
5-1. 보너스 번호 입력 받기
- [ ] 사용자가 1~45 범위 내 숫자 하나를 입력하여 보너스 번호를 설정합니다.

5-2. 보너스 번호 검증
- 예외 상황에서 오류 메시지를 출력하고 사용자에게 보너스 번호를 재입력 받습니다.
  - 예외 상황
  - [ ] 숫자 형식이 아닌 입력이 포함된 경우
  - [ ] 보너스 번호가 1~45 범위를 벗어난 경우

### 6. 당첨 결과 계산
6-1. 당첨 결과 계산
- [ ] 각 로또 번호와 당첨 번호를 비교하여 일치하는 숫자의 개수에 따라 당첨 점수를 계산합니다.
- [ ] 각 점수별 상금을 계산합니다.

### 7. 당첨 통계 계산 및 출력
7-1. 당첨 통계 출력
- [ ] 각 점수별 당첨 개수를 계산하여 출력합니다.

7-2. 수익률 계산 및 출력
- [ ] 총 상금을 기준으로 수익률을 계산하여 출력합니다.