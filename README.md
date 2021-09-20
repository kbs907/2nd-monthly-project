 # Autonomous driving using ultrasonic sensors through DQN learning
 
 ## Video
 [![Watch the video](https://img.youtube.com/vi/9c6YvIKOwF8/maxresdefault.jpg)](https://youtu.be/9c6YvIKOwF8)
 
 ## Goal
 
 초음파 센서를 활용한 주행
 
 순서
 1. 알고리즘 주행 
 2. QR코드 인식 
 3. 방향전환 
 4. 머신러닝(DQN) 주행 
 5. YOLO인식
 6. AR태그 주차

 ## Environment
 
 * Xycar Model B (ultrasonic sensor)
 * Ubuntu 16.04
 * ROS Kinetic
 * Nvidia TX2
 
 ## Role
 
 1. 알고리즘 주행
 2. 방향 전환
 3. 머신러닝(DQN) 주행
 
 ## Limitations
 
 시뮬레이션 상에서 학습시킬때에는 잘 동작하였지만, 학습된 모델을 xycar에 적용시켰을 때 시뮬레이터 상에서와 다른 동작을 보임


 ## What I've learned

 1. DQN 학습시 parameter와 reward가 주는 영향
 2. 시뮬레이션 상에서 학습된 모델을 실 환경에 적용하는데 어려움
