# Drowsiness-Detection
CNN을 활용하여 졸음을 예측해 졸음운전을 방지하는 프로젝트입니다.

# 주제 선정 이유
딥러닝을 통해 졸음을 미리 방지한다면 사고를 미리 예방할 수 있을 것 이라고 생각했습니다.

# 프로젝트 순서
1. 캐글에서 눈감은 사진 2000장과 눈 뜬 사진 2000장구함.
2. 모델의 성능을 높이기 위해 이미지 증식.
3. CNN모델을 쌓고 오버피팅을 방지하기위해 dropout 추가.
4. 모델의 정확도가 97.5%를 넘었기때문에 모델학습을 마침.
5. openCV를 이용해 얼굴에서 눈만 골라낸 후 그 눈을 이용해 테스트.
6. 테스트 결과 좋은 성능을 나타냄.
7. 웹캠을 통해 자신의 얼굴로 성능 테스트.
8. 테스트결과 눈을 감으면 시끄러운 새소리로 졸음을 미리 방지.

# 후기
프로젝트를 하는 도중 이러한 기술이 벌써 있다는 것을 알았습니다. 저도 이처럼 사고를 예방하거나 사회에 큰 영향력을 주는 모델을 개발하고싶다고 크게 느꼈습니다.
