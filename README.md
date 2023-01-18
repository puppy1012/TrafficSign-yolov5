# TrafficSign-yolov5
사물인터넷캡스톤 대비 커스텀 데이터 생성(roboflow) , train   
>roboflow를 통한 커스텀 데이터 업로드- 수동라벨링 작업 - yolov5 pytorch 버젼 데이터 다운 및 yolov5s train.py 실행  
>>사용 데이터셋 = /yolov5-master/Detect-TrafficSign.v2i.yolov5pytorch   
---------
train.py 진행시 사용한 코드   
>python train.py --img 640 --batch 32 --epochs 100 --data ./Detect-TrafficSign.v2i.yolov5pytorch/data.yaml --cfg ./models/yolov5s.yaml --weights yolov5s.pt
