핵심 로직
    전진조건 
    스캐너
UI 
    inputview
        댓수 횟수 입력?
    resultview
        결과 표현

초간단 자동차 경주 게임을 구현한다.
주어진 횟수 동안 n대의 자동차는 전진 또는 멈출 수 있다.
사용자는 몇 대의 자동차로 몇 번의 이동을 할 것인지를 입력할 수 있어야 한다.
전진하는 조건은 0에서 9 사이에서 random 값을 구한 후 random 값이 4이상일 경우이다.
자동차의 상태를 화면에 출력한다. 어느 시점에 출력할 것인지에 대한 제약은 없다.

기능 구현시 마다 커밋!

    // 1. 차량숫자 만큼 자동차를 만든다. ok
    // 2. 전진 할 로직 구현 // 랜덤넘버를 생성한다 ok
    // 3. 전진 하면 위치 기억 //램덤값이 4이상이면 앞으로 전진한다. ok
    // 4.게임 횟수만큼 2->3->4 로직을 반복 수행한다. ok
    // 5.화면에 출력한다. ok