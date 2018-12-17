# 武汉大学开源软件工程
# trash-classification
基于TensorFlow和Keras的智能垃圾分类系统。

## 一、	运行环境及依赖库

项目使用的python版本为python 3.6，所需的python模块包括:
Tensorflow 
Numpy
Keras
cv2
h5py

## 二、	训练数据

由于训练数据比较庞大，因此不上传到github，可在下列链接进行下载：
https://www.kaggle.com/asdasdasasdas/datasets。

## 三、源代码说明

train.py：用于训练垃圾分类模型
predict.py:用于加载垃圾分类模型
prepare_image.py:对需要进行预测的图片进行预处理
plot.py:对预测结果图片进行显示
main.py:调用各个模块对图片进行测试和显示结果

## 四、	使用指南
在main.py的main方法内，调用detect方法，并输入所需要进行预测的图片的路径，即可完成对图片的预测。



## 五、测试结果示例：

### 测试图片：
![github](https://github.com/cchangcs/trash-classification/blob/master/%E6%B5%8B%E8%AF%95/test_pics/3.jpg
"github") 

###  测试结果：

![github](https://github.com/cchangcs/trash-classification/blob/master/%E6%B5%8B%E8%AF%95/%E6%B5%8B%E8%AF%95%E7%BB%93%E6%9E%9C%E7%A4%BA%E4%BE%8B/cardboard_test_result2.png  "github")  
