# kotlin-racingcar-realtime

## 1단계 기능 요구 사항
### 실시간으로 자동차들이 독립적으로 움직이며, 가장 먼저 목표 거리에 도달한 1대의 자동차가 승리한다.

##### - 각 자동차는 별도의 코루틴에서 독립적으로 움직인다.
##### - 각 자동차는 0ms ~ 500ms 사이의 랜덤한 시간 동안 delay한 후, 1칸 전진한다.
##### - 매번 움직일 때마다 현재 위치를 즉시 출력한다.

###### feat1: 기본 정보 입력(자동차 이름, 목표 거리)
###### feat2: 각 차량 별 코루틴 생성 및 경주 진행하기
###### feat3: 먼저 도달한 차량 파악 및 모든 코루틴 종료시키기


## 2단계 기능 요구 사항
### 실시간으로 자동차들이 독립적으로 움직이며, 가장 먼저 목표 거리에 도달한 1대의 자동차가 승리한다.

##### - 사용자가 엔터를 입력하면, 경주를 일시 정지하고 입력 기회를 제공한다.
##### - add 자동차이름 명령어를 입력하면, 새로운 자동차가 즉시 경주에 합류하여 기존 자동차들과 동일하게 코루틴을 통해 독립적으로 움직인다.
##### - 입력 없이 엔터를 치면 경주를 다시 재개한다.

## 3단계 기능 요구 사항
### 실시간으로 자동차들이 독립적으로 움직이며, 가장 먼저 목표 거리에 도달한 1대의 자동차가 승리한다.

##### - 사용자가 엔터를 입력하면, 경주를 일시 정지하고 입력 기회를 제공한다.
| 명령어  |설명|
|------|---|
| add 자동차 이름 |새로운 자동차를 추가한다.|
| boost 자동차 이름 |해당 자동차의 이동 속도를 2배 빠르게 만든다.|
| slow 자동차 이름 |해당 자동차의 이동 속도를 2배 느리게 만든다.|
| stop 자동차 이름 |해당 자동차를 즉시 정지시킨다.|

##### - 입력 없이 엔터를 치면 경주를 다시 재개한다.
