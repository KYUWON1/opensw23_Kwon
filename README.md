# OPENSW Project
## Team introduction
* 202014185 심규원 개인프로젝트 조번호 3 
## Topic introduction
### 실시간 개체 감지 및 이미지 세분화 모델 Ultralytics YOLOv8
* 출처 yolov3 > https://github.com/ultralytics/yolov3<br/><br/>
* YOLOv3는 "You Only Look Once"의 약자로, 객체 감지(object detection) 작업에 사용되는 딥러닝 알고리즘입니다.<br/> https://github.com/ultralytics/ultralytics 에서 출시된 당사의 최신 최첨단(SOTA, state of the art) 모델입니다.<br/><br/>
* YOLOv3는 객체 감지를 위해 이미지나 비디오를 입력으로 받아들이고, 이미지에서 다양한 객체를 식별하고 해당 객체들의 경계 상자(bounding box)와 클래스 레이블(class label)을 출력합니다.<br/><br/>
* YOLOv3는 Convolutional Neural Network (CNN) 아키텍처를 기반으로 합니다. 이 아키텍처는 이미지를 여러 개의 그리드로 나눈 후, 각 그리드 셀마다 여러 개의 bounding box를 예측하고, 예측된 bounding box들을 필터링하여 객체를 식별하는 방식을 사용합니다.<br/> 또한, YOLOv3는 다양한 크기의 객체를 잘 탐지하기 위해 여러 개의 스케일로 예측을 수행합니다.<br/><br/>
* YOLOv3는 사전 학습된 가중치를 사용하여 객체 감지 작업을 수행할 수 있으며, 이를 통해 보다 빠르게 객체 감지 모델을 구축하고 사용할 수 있습니다.<br/> 또한, YOLOv3는 다양한 객체 클래스를 감지할 수 있으며, 사용자가 직접 데이터를 수집하거나 다양한 데이터셋을 사용하여 모델을 학습시킬 수 있습니다.<br/><br/>
* YOLOv3는 높은 정확도와 실시간 처리 속도를 동시에 제공하며, 이는 실시간 비디오 감시, 자율 주행 차량, 보안 시스템 등 다양한 응용 분야에서 유용하게 사용됩니다.<br/><br/>
* 광범위한 물체 감지, 이미지 분할 이미지 분류작업에 사용됩니다.<br/><br/>
* 요약하자면, YOLOv3는 Input으로 받은 이미지파일이나, 동영상, 동영상 링크등을 위에 적어둔 식별 방식을 통하여 객체가 식별된 이미지, 영상을 Output으로 제공하여줍니다. <br/><br/> 
* YOLOv3는 오픈 소스로 제공되며, 다양한 프레임워크를 통해 사용할 수 있습니다.<br/> 파이썬을 사용하여 YOLOv3를 구현하고 사용할 수 있는 라이브러리로는 Ultralytics의 "YOLOv3 🚀"이 있습니다.<br/><br/>
## Results

### YOLOv3 🚀 사용한 <br/>기존이미지 Detection 결과 1


![zed](https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/4ca9919a-d7d3-49d7-9554-d21a74045035)
![zidane b](https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/e4e24737-d862-4ef5-a96a-eaa5291582c0)
![zidane a](https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/1ed40dbc-40d0-440d-a63f-5b4004670c80)
### YOLOv3 🚀 사용한 <br/>기존이미지 Detection 결과 2


![code1](https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/0e634bc9-c379-4c70-8dc2-be81c5abd684)<br/>
![bus b](https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/7b68e431-2585-4fa8-ac72-2f287b73fa4b)
![bus a](https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/e3a8f334-75ea-42bd-962b-d7324312859e)

### 내가 찍은 이미지 Detection 결과


![test2](https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/56adcf89-01c9-4cea-965f-095ff824be8e) 
![test1](https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/9d6749d2-9ac1-4692-ad9b-431a2403f833)
![t1](https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/b85f2f93-8ee1-4183-abd2-f6b1cd64a064)
![t2](https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/c0fea109-f23e-4445-be14-8471d4eb8317)
![t3](https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/62d6dd19-4379-4f63-8a9e-b243752abdcf)
![t5](https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/4c41ac9b-ad05-4bea-9c3a-f2baaabf224c)
![t6](https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/ad3b1fbc-3e5c-4608-ab16-2eb7f7818d4a)
![t8](https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/3e81b051-57fd-45c6-abfa-a2c4c376076d)


### 웹캠를 통한 실시간 분석 화면



https://github.com/KYUWON1/KYUWON/assets/127181209/37fb9d08-2387-4c0a-94d2-89c4adcb3f31
### Youtube 링크 영상 분석 화면 



https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/4e44f958-ab46-4a8d-89a7-201cef03e7c2
### 휴대폰으로 직접 촬영한 YOLOv3 🚀을 이용한 자율주행 시뮬레이션



https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/3cdfd62b-0069-484d-95fa-0380cb0e601e



## Analysis/Visualization
### -Yolov3를 통한 Object detection을 직접 실행해보았는데, 우선 사용자가 명령어를 통해 사용하기 매우 편리했습니다.<br/> -이미지 파일, 동영상 아니면 Object detection을 하고 싶은 자료들을 폴더에 모아놓고 한번에 폴더 자체를 실행할수도있었고, 링크를 걸어주어도 해당 링크 자료를 판별한 결과물도 출력해줍니다.<br/>-성능을 보았을땐, 전반적으로 사물을 잘 인식해주는것으로 보입니다.<br/> 물론 사진속에 모든 사물들을 세세히 전부다 탐지해주지는 않지만, 사전에 Train된 이미지들에 대해서는 Result에 웹캠 영상이나, 사진 결과물들을 보시면 알수있듯 대부분 잘 인식해 주었습니다.<br/>-Detection의 유사도를 측면에서 보았을땐, 유사도가 0.4퍼센트 이상 넘어가면, 보통 올바르게 사물을 인식했고, 0.4퍼센트 미만으로 내려가면, 정답률이 약간씩 떨어지는 것을 볼 수 있었습니다.<br/>-Result에 보여준 예시 사진외에도, 제가 많은 Test를 수행해본 결과, 다른 물체들은 탐지하지 못하거나, 정답이 틀리더라도, 사람은 거의 100% 확률로 탐지하고 사람으로 인식하는 것을 볼 수 있었습니다. 

 

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

https://youtu.be/ipqckes6QKg

