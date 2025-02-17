# Ultralytics-OneClick
Ultralytics-YOLO11 免安装一键启动整合包

## Ultralytics说明
Ultralytics YOLO11是一款尖端、最先进的（SOTA）型号，它建立在之前YOLO版本的成功之上，并引入了新的功能和改进，以进一步提高性能和灵活性。YOLO11的设计快速、准确、易于使用，使其成为各种目标检测和跟踪、实例分割、图像分类和姿态估计任务的绝佳选择。

为方便大家快速上手体验，省去安装部署耗时，我制作了最新版一键启动整合包

## Ultralytics整合包使用说明

软件下载解压后直接双击【启动软件.exe】即可打开UI界面。

首先选择待处理文件，可以是图片或视频的路径地址，如果选择处理摄像头内容的话输入框里填0

保存位置即处理结果保存目录

模型即yolo模型

置信度阈值就是物体识别检测结果是否更可靠更接近1，如果识别物体值低于这个值的话就不标记处理。置信度阈值范围（0~1），自己操作一下就明白效果了。

IoU 阈值（0~1）用于衡量预测的边界框与真实目标的边界框之间的重叠程度。

指定类别就是你想要检测什么物体，0人，1自行车，2汽车，只检测人的话这里就填0，人和汽车，这里就填0,2，用英文逗号隔开。

视频教程：[youtube>>](https://www.youtube.com/watch?v=kSG0oyrcVY4)

## 注意事项

整合包只支持Windows 10或11系统

软件运行路径中不要有非英文字符和空格

## ultralytics一键启动整合包下载链接

https://pan.baidu.com/s/1vH3bYqrNhwN3NhbmG3F2Zw?pwd=2ct9

## YOLO物体类别代码如下

索引	类别名称	索引	类别名称	索引	类别名称
0	person（人）	1	bicycle（自行车）	2	car（汽车）
3	motorcycle（摩托车）	4	airplane（飞机）	5	bus（公交车）
6	train（火车）	7	truck（卡车）	8	boat（船）
9	traffic light（红绿灯）	10	fire hydrant（消防栓）	11	stop sign（停车标志）
12	parking meter（停车计时器）	13	bench（长凳）	14	bird（鸟）
15	cat（猫）	16	dog（狗）	17	horse（马）
18	sheep（羊）	19	cow（牛）	20	elephant（大象）
21	bear（熊）	22	zebra（斑马）	23	giraffe（长颈鹿）
24	backpack（背包）	25	umbrella（雨伞）	26	handbag（手提包）
27	tie（领带）	28	suitcase（行李箱）	29	frisbee（飞盘）
30	skis（滑雪板）	31	snowboard（单板滑雪）	32	sports ball（球）
33	kite（风筝）	34	baseball bat（棒球棒）	35	baseball glove（棒球手套）
36	skateboard（滑板）	37	surfboard（冲浪板）	38	tennis racket（网球拍）
39	bottle（瓶子）	40	wine glass（酒杯）	41	cup（杯子）
42	fork（叉子）	43	knife（刀）	44	spoon（勺子）
45	bowl（碗）	46	banana（香蕉）	47	apple（苹果）
48	sandwich（三明治）	49	orange（橙子）	50	broccoli（西兰花）
51	carrot（胡萝卜）	52	hot dog（热狗）	53	pizza（披萨）
54	donut（甜甜圈）	55	cake（蛋糕）	56	chair（椅子）
57	couch（沙发）	58	potted plant（盆栽）	59	bed（床）
60	dining table（餐桌）	61	toilet（厕所）	62	TV（电视）
63	laptop（笔记本电脑）	64	mouse（鼠标）	65	remote（遥控器）
66	keyboard（键盘）	67	cell phone（手机）	68	microwave（微波炉）
69	oven（烤箱）	70	toaster（烤面包机）	71	sink（洗手池）
72	refrigerator（冰箱）	73	book（书）	74	clock（时钟）
75	vase（花瓶）	76	scissors（剪刀）	77	teddy bear（泰迪熊）
78	hair drier（吹风机）	79	toothbrush（牙刷）	–	–

## ultralytics 项目链接
https://github.com/ultralytics/ultralytics
