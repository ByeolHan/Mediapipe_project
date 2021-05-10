# Mediapipe_project
Vehicle_intelligence_Mediapipe_project

# **손카; 손과 차의 커뮤니케이션** :open_hands::blue_car:
: 커넥티드 카의 음성인식 기술의 단점을 보완할 수 있는 손동작 인식 기술

## 예상성과
* 농아인들의 편리한 운전 감성 경험을 도울 수 있다. 
* 지역 방언에 상관없이 기술을 사용할 수 있다.
* 제스처를 지정한다면, 언어에 국한되지 않고 사용될 수 있다. 
 * 자율주행이 구현된 상황, 공유 모빌리티에서 유용하게 사용될 수 있다.)  
* 기타 활동으로 인한 영상, 음성 등의 소음에 영향을 받지 않고 차량을 제어할 수 있다. 

## 구현과정
- Mediapipe의 Pose classifcation(basic)을 이용 
- hand gesture 이미지들의 landmark 정보들을 csv 파일로 받은 후 
- sklearn 머신러닝 모델들을 이용하여 학습
- 가장 정확도가 높은 RandomForestClassifier 모델을 이용하여 pose 사진과 동영상에 클래스& 확률 나타내기

# reference
- https://github.com/google/mediapipe.git
- https://github.com/nicknochnack/Body-Language-Decoder.git
