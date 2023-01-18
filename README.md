# TrafficSign-yolov5
사물인터넷캡스톤 대비 커스텀 데이터 생성(roboflow) , train
python train.py --img 640 --batch 32 --epochs 100 --data ./Detect-TrafficSign.v2i.yolov5pytorch/data.yaml --cfg ./models/yolov5s.yaml --weights yolov5s.pt
