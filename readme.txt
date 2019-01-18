FacialKeypointsDetection人脸特征识别

data文件夹中为原始数据文件
...

code文件夹中为执行代码：
程序是在Jupyter notebook中运行的
FKD_Keras.ipynb：
缺失值用上一行数据值（ffill）填补，尝试用Keras预测填补缺失值，但实际效果不理想。
使用了Keras人工神经网络训练模型，kaggle最终得分误差为4.13
使用CNN测试,测试时间大幅增加，且准确率不高
Tensorflow框架测试，应该是调参问题，未达效果。