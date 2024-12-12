# 9517 - Turtle Identification and Labeling 图像分割项目

### 项目介绍：
  在该项目中，我们使用多种CNN神经网络（U-net, FCN, Deeplabv3, Deeplabv3+）模型对海龟的不同部位（如头部、鳍、身体）进行分割识别，使用了8000多张的海龟图片进行学习，计算学习损失并在测试和验证集中计算iou和miou评估模型进行对比。尝试调整超参数优化模型，最后编写投票集成模型得到最优结果。

### 项目组成：
- proj_code 各模型代码
- proj_report 项目报告

### 项目思想： 
- 1.Create data dictionary by train, valid and test
- 2.Set class dataset by using coco
- 3.Create dataset for train, valid, test
- 4.divide dataset into samll dataset in order to improving effiency
- 5.Show dataloader size and dataset size
- 6.Using deeplabv3 model to get iou and miou


