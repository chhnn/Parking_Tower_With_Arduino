# Parking-Tower
 Parking Tower with Arduino

"If the .ino file does not open, check the .txt file."
-------------------------------------------------------
[Program Execution Process Summary]
1. The direction of laser A and B is towards the light sensor. Laser A is always on. The motor operates when laser light enters the light sensor.
2. LaserB is connected to Bluetooth.
3. When the light from laser A is obscured by the parking space, the motor stops.
4. Receive input from the user via Bluetooth, activate the laser B, allowing the motor to turn again.
LCD monitors are printed separately when the parking space is coming and when it is arrived.
When coming, +1 is given to the user to show 1, 2, 3, and 4 parking spaces.
When arrived, 0 of the remaining values divided by 4 adds 4 so that the user can see 1, 2, 3, and 4 parking spaces.

-------------------------------------------------------
[프로그램 실행과정 요약]
1. 레이저A와 B의 방향은 조도센서를 향해 있음. 레이저A가 항상 켜져있음. 조도센서에 레이저 빛이 들어오면 모터가 작동함.
2. 레이저B는 블루투스와 연결되어 있음.
3. 주차공간에 의해 조도센서에 들어오는 레이저A의 빛이 가리게 되면 모터가 멈춤.
4. 블루투스를 통해 사용자에게 입력을 받아, 레이저B를 작동시켜 모터가 다시 돌게끔 함.
LCD모니터에는 주차공간이 coming일 때와 arrived일 때의 경우를 나누어 출력함.
coming일 땐 0,1,2,3의 값에 +1을 해줌으로써 사용자에게 1,2,3,4번의 주차공간으로 보여지게 함.
arrived일 땐 4로 나눈 나머지값들 중 0에는 4를 넣어 사용자에게 1,2,3,4번의 주차공간으로 보여지게 함.