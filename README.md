# MNIST2
6.Keras MNIST手写数字识别数据集；7.Keras多层感知器识别手写数字；8.Keras卷积神经网络识别手写数字 

目的：主要利用Keras模块实现手写数字的识别

所用模块：Keras，numpy，pandas，matplotlib

主要函数及作用：

plot_images_labels_prediction:
方便地查看数字图形，真是的数字与预测结果。参数：images（数字图像）、 label（真实值）、 prediction（预测结果） idx（开始显示的数据index）、 num（要显示的数据项数，默认是10，不超过25）

show_train_history:
设计函数用于显示训练过程。参数：train_history（之前训练过程所产生的train_history）、 train（训练数据的执行结果）、 validation（验证数据的执行结果）
