# OPENSW Project
## Team introduction
* 202014185 심규원 개인프로젝트 조번호 3 
## Topic introduction
### 실시간 개체 감지 및 이미지 세분화 모델 Ultralytics YOLOv8
* https://github.com/ultralytics/ultralytics 에서 출시된 당사의 최신 최첨단(SOTA, state of the art) 모델입니다.
* 광범위한 물체 감지, 이미지 분할 이미지 분류작업에 사용됩니다.
* YOLOv8은 딥 러닝 및 컴퓨터 비전의 최첨단 발전을 기반으로 구축되어 속도와 정확성 측면에서 비교할 수 없는 성능을 제공합니다.<br/> 
간소화된 디자인 덕분에 다양한 애플리케이션에 적합하고 에지 장치에서 클라우드 API에 이르기까지 다양한 하드웨어 플랫폼에 쉽게 적응할 수 있습니다.
## Results
* 기존이미지 Detect 결과 1


![zed](https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/4ca9919a-d7d3-49d7-9554-d21a74045035)
![zidane b](https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/e4e24737-d862-4ef5-a96a-eaa5291582c0)
![zidane a](https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/1ed40dbc-40d0-440d-a63f-5b4004670c80)
* 기존이미지 Detect 결과 2


![code1](https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/0e634bc9-c379-4c70-8dc2-be81c5abd684)
![bus b](https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/7b68e431-2585-4fa8-ac72-2f287b73fa4b)
![bus a](https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/e3a8f334-75ea-42bd-962b-d7324312859e)



![test2](https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/56adcf89-01c9-4cea-965f-095ff824be8e) 
![test1](https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/9d6749d2-9ac1-4692-ad9b-431a2403f833)
* 카메라를 통한 실시간 분석 화면


![test3](https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/90981650-9aa1-4a6e-83d7-b295eae94144)
* Youtube 링크 영상 분석 화면 


https://github.com/KYUWON1/opensw23_Kwon/assets/127181209/4e44f958-ab46-4a8d-89a7-201cef03e7c2

## Analysis/Visualization
## Installation
* git bash를 실행합니다
* 원하는 repository로 이동 합니다. 
* git bash 창에 순서대로 명령어를 입력합니다.
1. git init
2. pip install ultralytics
3. git clone https://github.com/KYUWON1/opensw23_Kwon 
4. cd opensw23_Kwon
5. cd yolov3  #출처 https://github.com/ultralytics/yolov3
6. pip install -r requirements.txt
7. python detect.py --weights yolov5s.pt --source args<br/>
>   args :<br/> 
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
>   ex)  python detect.py --weights yolov5s.pt --source data/images/bus.jpg
8. 실행이 완료되면 detection이 끝난 파일들은 runs 폴더 안에 저장됩니다.
## Presentation

