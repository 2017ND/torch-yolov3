1.训练自己数据时，需要进行fine-tuning,加载预训练模型darknet53.conv.74或者yolov3-tiny.conv.15
训练脚本比如：python train.py --data XXX --weights XXX --cfg XXX --batch-size X --epochs X
2.python detect.py --data XXX --weights XXX --cfg XXX --save-txt   (注意：如需保存结果txt，必须加--save-txt)  默认是检测data/samples/图片
3.python detect.py --data XXX --weights XXX --cfg XXX --source 0/rtsp:XXX (注意：--source为配置视频源，0为本地电脑摄像头，rtsp为网络地址)
