# yolo_truck

打开floyd客户端


floyd login --username aa --password bb

H:


cd H:\deeplearning\floydhub\yolo1


floyd init quick-start


floyd run --data sanfooh15/datasets/darknet19_448conv23:/data --gpu --mode jupyter


1、使用run.bat 登陆，具体信息要改


2、打开terminal,切到根目录,


git clone https://github.com/sanfooh/darknet_for_floydhub.git


mv darknet_for_floydhub darknet


cd darknet


git clone https://github.com/sanfooh/yolo_truck.git


mv yolo_truck work


./darknet detector train work/cfg/obj.data work/cfg/YOLO-obj.cfg /data/darknet19_448.conv.23
