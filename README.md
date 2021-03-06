# dadafountain
天气以及时间分类
赛题名称
天气以及时间分类

https://www.datafountain.cn/competitions/555

赛题背景
在自动驾驶场景中，天气和时间（黎明、早上、下午、黄昏、夜晚）会对传感器的精度造成影响，比如雨天和夜晚会对视觉传感器的精度造成很大的影响。此赛题旨在使用Oneflow框架对拍摄的照片天气和时间进行分类，从而在不同的天气和时间使用不同的自动驾驶策略。

赛题任务
此赛题的数据集由云测数据提供。比赛数据集中包含3000张真实场景下行车记录仪采集的图片，其中训练集包含2600张带有天气和时间类别标签的图片，测试集包含400张不带有标签的图片。

本赛题的数据集包含2600张人工标注的天气和时间标签。天气类别包含多云、晴天、雨天、雪天和雾天5个类别；时间包含黎明、早上、下午、黄昏、夜晚5个类别。 部分数据可视化及标签如下：
![image](https://user-images.githubusercontent.com/87884495/147173199-181af355-f016-4a50-97d2-c68abb491e32.png)
数据集包含anno和image两个文件夹，anno文件夹中包含2600个标签json文件，image文件夹中包含3000张行车记录仪拍摄的JPEG编码照片。图片标签将字典以json格式序列化进行保存：
![image](https://user-images.githubusercontent.com/87884495/147173229-13416fad-d19a-450d-873c-bf93f6dd8118.png)
