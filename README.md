- 컴포지션 : 영상을 표현하는 부분 

- 레이어 : 영상 내의 층, 컴포넌트 내의 층 
    - solid : 평면
    - null : 빈 객체 , parent 위주로 디테일하게 작업할때
    - Shape Layer : 여러가지 모양을 가진 객체
    - Adjustment Layer : 원하는 범위 안에서 이펙트를 조정하려고 할때 사용

- 펜툴 : 솔리드를 깔고 그위에 마스크를 씌움 
    - 솔리드 객체 내에 마스크 패널에 펜툴로 작업한 마스크들이 존재.
    - 마스크 패스 : 경로 or 모양
    - 마스크 페더 : 가장자리를 다룸
    - 마스크 불투명도 : 투명도
    - 마스크 확장 : 펜툴의 한계점 보다 작게 또는 크게 설정
     
- MASK : 보여주고 싶은 부분만 보여줌, 피객체가 같이 따라옮

- MATTE : 마스크와 동일하지만 피객체와 분리되어있음
    - 알파매트 : 투명도와 불투명으로 다룸
    - 루나매트 : 검정색과 흰색으로 다룸 
    

- 하이어라키 : 객체간에 연결 시키고, 종속관계로 폴더링 
goh@wootcreative.kr

# 툴박스

기준점 도구 : 이펙트 축을 변경
퍼핏 핀 : 관절과 축을 다룸

#그래프 

speed graph : y축이 속도를 뜻함
value graph : 빨간색이 x출이고 초록생이 y축이며, 상대적인 위치를 뜻 

# 폴더 트리

- @@MainCamp : 골뱅이를 넣어줌으로써 가장 산단으로올림
- 01_Ai = 일러스트
- 02_PSD = 포토샵
- 03_Sequnce = 3D

# Tip

- alt + 확대축소 
- 키전체선택 + (마지막 또는 첫번째 키) 선택 + 드래그 = 비율을유지하면서 프레임 조절 
- n & b : 
- cmd + d = 복사
- cmd + shift + d = 복사와 동시에 좌우축으로 끊음 
- cmd + shift + c = 선택된 소스를 컴포지션으로 묶음 ( 두번째 항목 선택 )
- cmd + k = 컴포지션 사이즈 변경
- alt + [ or ]  : 레이어 커팅
- shift + control + Y : 컬러 변경
- 컴트작업시 : 자물쇠 잠금 -> New comp Viewer => 화면이 나눠짐


# Others 

- 종속시키기
- 레이어 길이 위치 조정
- Rove Across Time : 지점만 가지고, 속도는 가지지 않는 지점
- 보간 계산 : Postion Subframe
- Keyframe Assistant -> rever key frame : 반대로 돌음 
- Enable Time Remaping : 컴포지션의 구간과 순서를 컨트롤할수있
- Rove Across Time : 자연스럽게 넘어감
- Key frame velocity
- 가이드 레이어 : 컴프이름앞에 #이 붙으며 렌더링시 보이지 않음
- CC : 유명한 라이브러리를 어도비에서 산 라이브러리 계열


네이밍 컨벤션 



# 일러스트레이터 파일을 임포트 할 때

1. Release to Layer를 통해 분할
2. Release to Layer(Sequence)의 경우, 그룹은 건들지않음

# 카메라

- type : two-node camera : 중심축을 앞에 놓는 앵커 포인트가 생김 
- 카메라는 널에 연결해서 쓰는게 좋음, 널의 이름은 cam control 이라 주로 
- orientation과 rotation : orientation는 초기값 , rotation은 추후 변경 값 위주
- Auto Orient : 화면을 계속 주시하게 만듬
- Scale : 카메라와의 카메라 컨트롤러간 거리를 조절할 수 있음

# Light

복습하기


# Effects

- ![Effect](https://github.com/banziha104/AfterEffect/blob/master/Effects.md)

# Particular 

- ![Particular](https://github.com/banziha104/AfterEffect/blob/master/Particular.md)

# Duik

- ![Duik](https://github.com/banziha104/AfterEffect/blob/master/Particular.md)

# Expression

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


        
- Bones : 퍼펫을 관절로 만듬

# 팁

- Layer -> Auto Trace : Png 파일을 벡터이미지로 전환 