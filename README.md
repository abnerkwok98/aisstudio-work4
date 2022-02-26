# aisstudio-work4
# 使用鸽子数据集做基于PaddlePaddle的图像分割任务
## 1.简介
本项目完成一个图像语义分割任务。
## 2.数据集
使用[鸽子数据集](https://aistudio.baidu.com/aistudio/datasetdetail/75217)来完成训练与测试
此数据集的组成形式如下：
> doves
> > IMG_4705
> > > * img.png
> > > * label.png
> > > * label_names.txt
> > > * label_viz.png
## 3.训练环境
PaddlePaddle 2.0.2

硬件环境：
|  环境   | Paddle高级GPU  |
|  ----  | ----  |
| CPU  | 2 |
| RAM | 16GB |
| GPU  | v100 |
| 显存  | 16GB |
| 磁盘  | 100GB |
## 4.训练模型
训练前先下好code文件夹
