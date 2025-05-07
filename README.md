# Object_Detection_yolov5
이전 프로젝트의 pyqtgui001 프로젝트에서 추가적으로 지난 시간에 주차장 빈자리 찾는것을 학습시켜 얻은 best.pt를 카메라에 인식을 하도록 추가하였습니다.   
이전의 프로젝트를 복사하여 pyQT002_yolov5 폴더를 만들어 이를 주 프로젝트 폴더로 하였습니다. 복사한 후 가상환경 만드는 것은 생략하고 먼저 yolov5를 아래의 이미지를 통해 복사하여 프로젝트 파일에 추가합니다.   
yolov5폴더는 용량이 큰 관계로 아래의 이미지와 같이 프로젝트 파일에 추가하였습니다.   
![터미널](https://github.com/jjkkhh123/Object_Detection_yolov5/blob/main/images/terminal.png)   
#
저는 main.py만을 수정하여 기능을 구현하였습니다. 추가한 코드만을 다뤄 보자면 아래의 이미지와 같이 yolov5의 경로를 추가해줍니다. 그리고 경로의 detect파일의 run을 사용하기위해 준비힌 코드입니다.
![경로](https://github.com/jjkkhh123/Object_Detection_yolov5/blob/main/images/code_1.png)
#
이후 yolov5모델을 로드하면서 best.pt도 가져와줍니다.
![best.pt로드](https://github.com/jjkkhh123/Object_Detection_yolov5/blob/main/images/code_2.png)
#
이후에 실행을 한 모습입니다.
![실행 화면](https://github.com/jjkkhh123/Object_Detection_yolov5/blob/main/images/simulation.png)

# 
보완점은 학습을 시킨게 외국의 주차장을 위주로 학습을 하다보니 국내 주차장에 취약한 모습을 보입니다.
