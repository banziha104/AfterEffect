# Expression

> 자바스크립트로를 기반으로하며, 일종의명렁어집합

사용법 : 적용하고자 하는 곳에 alt를 누르고 키 버튼
- wiggle(x,y) : x는 주기 y는 수치, 랜덤하게 움직임 slider와 같이 쓰임
- time*x : 초당 x번 회전
- loopIn("cycle",0) : 종료점을 지정할 수 있음 , 뒤의 매개변수는 구간을 지정, 0은 전체 구간을 반복,
- loopOut("cycle",0) : 시작점을 지정할 수 있음
- loopInDuration("cycle",0) : 
- loopOutDuration("cycle",0) :
    - cycle : 일정 시간 동안 한방향으로 움직임
    - pingpong :양방향으로 토글됌
    - offset : 이전 단계에 더해서 반복함
    - continue : 마지막 각도에 기반해 진행함, 뒤의 인자 불필요
