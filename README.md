# OPENSW Project
## Team introduction
* 202014185 심규원 개인프로젝트 조번호 3번
## Topic introduction
### 실시간 개체 감지 및 이미지 세분화 모델 Ultralytics YOLOv8
#### * 출처 yolov3 > https://github.com/ultralytics/yolov3<br/><br/>
* YOLOv3는 "You Only Look Once"의 약자로, 객체 감지(object detection) 작업에 사용되는 딥러닝 알고리즘입니다.<br/> https://github.com/ultralytics/ultralytics 에서 출시된 당사의 최신 최첨단(SOTA, state of the art) 모델입니다.<br/><br/>
* YOLOv3는 객체 감지를 위해 이미지나 비디오를 입력으로 받아들이고, 이미지에서 다양한 객체를 식별하고 해당 객체들의 경계 상자(bounding box)와 클래스 레이블(class label)을 출력합니다.<br/>![12341](https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/7756176b-1a74-45a4-b34b-bff6ee98b452)
* YOLOv3는 Convolutional Neural Network (CNN) 아키텍처를 기반으로 합니다. 이 아키텍처는 이미지를 여러 개의 그리드로 나눈 후, 각 그리드 셀마다 여러 개의 bounding box를 예측하고, 예측된 bounding box들을 필터링하여 객체를 식별하는 방식을 사용합니다.<br/> 또한, YOLOv3는 다양한 크기의 객체를 잘 탐지하기 위해 여러 개의 스케일로 예측을 수행합니다.<br/><br/>
* YOLOv3는 사전 학습된 가중치를 사용하여 객체 감지 작업을 수행할 수 있으며, 이를 통해 보다 빠르게 객체 감지 모델을 구축하고 사용할 수 있습니다.<br/> 또한, YOLOv3는 다양한 객체 클래스를 감지할 수 있으며, 사용자가 직접 데이터를 수집하거나 다양한 데이터셋을 사용하여 모델을 학습시킬 수 있습니다.<br/><br/>
* YOLOv3는 높은 정확도와 실시간 처리 속도를 동시에 제공하며, 이는 실시간 비디오 감시, 자율 주행 차량, 보안 시스템 등 다양한 응용 분야에서 유용하게 사용됩니다.<br/><br/>
* 광범위한 물체 감지, 이미지 분할 이미지 분류작업에 사용됩니다.<br/><br/>
### * 요약하자면, YOLOv3는 Input으로 받은 이미지파일이나, 동영상, 동영상 링크등을 위에 적어둔 식별 방식을 통하여 객체가 식별된 이미지, 영상을 Output으로 제공하여줍니다. <br/><br/> 
* YOLOv3는 오픈 소스로 제공되며, 다양한 프레임워크를 통해 사용할 수 있습니다.<br/> 파이썬을 사용하여 YOLOv3를 구현하고 사용할 수 있는 라이브러리로는 Ultralytics의 "YOLOv3 🚀"이 있습니다.<br/><br/>
## Results
### 저는 이미지 약50개, 동영상 5개, 웹캠, 유튜브 링크 1개를 직접 Detection 해보았습니다.<br/> Results 결과에는 개인적인 사진을 제외한 잘 인식된 사진 6장 실패한 사진 1장 ,웹캠 영상, 동영상 1개의 Detection 완료된 결과물들을 링크하였습니다.<br/><br/>개인적으로 직접 동영상을 한번 촬영하고 Test해보시는것을 추천드립니다.
### YOLOv3 🚀를 이용한 내가 찍은 이미지 Detection


![test2](https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/56adcf89-01c9-4cea-965f-095ff824be8e) 
![test1](https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/9d6749d2-9ac1-4692-ad9b-431a2403f833)
#### -Left image(판별전), Right image(판별후) 사람1명, 물병1개 Detection
![t1](https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/b85f2f93-8ee1-4183-abd2-f6b1cd64a064)
![123123](https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/739fdac5-7678-412c-b8cb-fdfc8fc1d84b)
#### -Left image(신호등 2개, 차량1대 Detection)<br/>-Right image (가로등, 나무 Detection 실패)
![t3](https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/62d6dd19-4379-4f63-8a9e-b243752abdcf)
![t5](https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/4c41ac9b-ad05-4bea-9c3a-f2baaabf224c)
#### -Left image(벤치 2개이지만 3개로 Detection)<br/>-Right image(사람 2명 Detection, 킥보드, 신호등 Detection Miss)
![t6](https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/ad3b1fbc-3e5c-4608-ab16-2eb7f7818d4a)
![t8](https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/3e81b051-57fd-45c6-abfa-a2c4c376076d)
#### -Left image(고양이 1마리 Detection)<br/>-Right image(차량 2대, 신호등 Detection, 가로등, 표지판 Detection 실패)<br/>


### YOLOv3 🚀를 이용한 웹캠을 통한 실시간 분석 화면



https://github.com/KYUWON1/KYUWON/assets/127181209/37fb9d08-2387-4c0a-94d2-89c4adcb3f31

### 제 방에서 노트북의 웹캠으로 촬영하면서 녹화한 영상입니다.<br/>사람 1명, 뒤에 있는 콜라 페트병들, 휴대폰들이 잘 인식되는것으로 보이고, 가위는 잘 판별하지 못 하는것으로 보입니다.<br/>

### 휴대폰으로 직접 촬영한 YOLOv3 🚀를 이용한 자율주행 시뮬레이션



https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/3cdfd62b-0069-484d-95fa-0380cb0e601e
### 운전하면서 친구가 제 핸드폰으로 직접 촬영해준 영상입니다<br/>주행하면서 실시간으로 승용차, 트럭, 버스, 신호등 , 걸어가는 사람들, 오토바이, 햇빛가리게등이 식별된 영상입니다.<br/>


## Analysis/Visualization

### 1. 유용성 측면<br/>
### -Yolov3를 통한 Object detection을 직접 실행해보았는데, 우선 사용자가 명령어를 통해 사용하기 매우 편리했습니다.<br/><br/> -이미지 파일, 동영상 아니면 Object detection을 하고 싶은 자료들을 폴더에 모아놓고 한번에 폴더 자체를 실행할수도있었고, 링크를 걸어주어도 해당 링크 자료를 판별한 결과물도 출력해줍니다.<br/>
### 2. 성능 측면<br/>
![dog1](https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/89c697a8-aef2-4a4c-80e4-b7197c99426d)
![dog2](https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/036eca1e-48e2-48ea-aec7-35067cb638d2)
### 왼쪽에 이미지는 저희집 강아지 사진이고, 오른쪽도 같은 각도에서 찍은 사직입니다.<br/>왼쪽 사진에서는 정확하게 강아지를 인식했지만, 오른쪽 사진처럼 만약 사물 중간에 어떤 사물이 개입되면, 강아지를 재대로 인식하지 못하는 것을 확인했습니다.<br/><br/>

![cb](https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/840270c2-c8f3-4bd9-839e-ab99eb318c27)
![cat](https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/36cd60e8-dd50-4384-a289-f9bf102ca4f3)
![cd](https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/3ce327bc-ae26-4f9f-80d5-a4ba1fc7b2b2)
### 이번에는 밝기에도 잘 적응하여 동작하는지 테스트해보았습니다.<br/>순서대로 밝음 - 보통 - 어두움 사진인데, 어두울때는 유사도는 좀 떨어지지만 잘 인식했지만, 밝을때는 유사도도 떨어질 뿐만아니라, 뒤에 판을 Tv로 잘 못 인식하는 것을 확인했습니다.<br/><br/>


https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/6f913712-3235-427a-af04-cf2fd6e26818
### 이번에는 화면 흔들림 테스트를 해보았는데, 보이는 영상에 전봇대 옆에는 할아버지 두 분이 계십니다.<br/>화면을 보시면 초반에 할아버지 두 분을 인식하지 못하다가 나중에 가서야 인식하는것을 볼 수 있었습니다.<br/><br/>
### -제가 테스트하여 성능을 보았을땐, 제 입장에선 전반적으로 사물을 잘 인식해주는것으로 보입니다.<br/>물론 사진속에 모든 사물들을 세세히 전부다 탐지해주지는 않지만, 사전에 Train된 이미지들에 대해서는 Result를 보시면 알수있듯 비교적 잘 감지했습니다.<br/>

<img width="1097" alt="result image" src="https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/20daf694-c959-43a3-99a6-92a19a926ef5">

### -Yolov3는 성능 측면에서는 약간 아쉽다는 평가를 받았지만, 위에 그래프를 보면 알수 있듯이, 추론속도가 아주 아주 빨라 저자가 미리 그린 그래프의 최솟값를 뚫고 나온것처럼 표를 작성해 놓았습니다.<br/><br/>-추론 측면에서는 이 정도 속도에 그 정도 성능이면 나름 괜찮다는 의견도 있습니다.
  







 

## Installation
* Windows11 환경에서 실행
* git bash 를 실행합니다.
* 원하는 repository로 이동 합니다. 
* git bash 창에 순서대로 명령어를 입력합니다.
1. git init
2. pip install ultralytics
3. git clone https://github.com/KYUWON1/opensw23_Kwon 
4. cd opensw23_Kwon  ## yolov3 출처 https://github.com/ultralytics/yolov3
5. pip install -r requirements.txt
6. python detect.py --weights yolov5s.pt --source args<br/>
>   args : 아래 표를 참고하여 args값에 원하는 값을 넣으시면됩니다.<br/> 
>   0                               #webcam<br/>
>   img.jpg                         #image<br/>
>   vid.mp4                         #video<br/>
>   screen                          #screenshot<br/>
>   path/                           #directory<br/>
>   list.txt                        #list of images<br/>
>   list.streams                    #list of streams<br/>
>   'path/*.jpg'                    # glob<br/>
>   'https://youtu.be/Zgi9g1ksQHc'  #YouTube<br/>
>   'rtsp://example.com/media.mp4'  # RTSP, RTMP, HTTP stream<br/><br/>
>   ●예시에 Detection된 이미지를 얻기 위해선 아래 명령어를 입력하시면 됩니다.<br/>
>   ex)  python detect.py --weights yolov5s.pt --source data/images/bus.jpg<br/>
>   ex)  python detect.py --weights yolov5s.pt --source data/images/zidane.jpg<br/>
8. 실행이 완료되면 detection이 끝난 파일들은 runs 폴더 안에 저장됩니다.

## Presentation
### 발표영상 Youtube 링크<br/>
https://youtu.be/ipqckes6QKg

