# Face-Detection 커스텀

## 소개
Front-End에서 사용할 얼굴인식 모델 사용법입니다. Windows10 WebCam에서 테스트를 마친상태입니다.
해당 모델은 Face Spoofing 방지가 이뤄지지 않는 모델입니다. 따라서 정확한 사용자 분류는 BackEnd의 모델에서 진행될 예정입니다.
## 사용 내역
얼굴이 인식되고 나서 몇 초간 인식이 이뤄져야 사용자가 얼굴인식 준비를 완료한 상태로 판단하고 서버에 요청할 용도로 사용할 것입니다.
## 커스텀기능
카메라상에서 얼굴이 인식되면 몇 초간 사람이 인식되었는지 Console 창을 통해서 확인할 수 있습니다.
모델은 평가한 점수 또한 함께 확인할 수 있습니다.
## 출처
해당 내용은 본 Repo를 Fork하여 커스텀하였음을 알려드립니다.
[ https://github.com/WebDevSimplified/Face-Detection-JavaScript ]
