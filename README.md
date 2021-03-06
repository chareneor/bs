# 毕业设计：照片自动归类于分发系统
##  设计并实现一个内容共享平台
###  要求：


*  实现照片的识别，采用一些基本的已有的照片识别代码，实现照片中任务的识别。
* 根据任务识别的结果，将照片分发给对应的用户。
_ _ _ 
_ _ _

### 具体思路：

* 从一张照片中识别人脸

* 将人脸截出并放缩至合适尺寸

*  __注意__ ：*当一张图片包含多个人脸时应当将每一张照片名作文文件夹名，在此文件夹中应该顺序将截出的人脸命名*

*  图像预处理模块完成（将之前代码整理成一个函数）

*  将需要识别的人脸照片进行提取特征并存入数据库（ 进行数据库的建立以及样本照片数据库的选取）

*  需要通过样本进行训练比较模型，之后在进行比较识别（模型的选择）

*  与需要进行识别的照片进行比较（可以自动加入新的特征，并且与存储的特征比较进行更新）

*  采用opencv对视频进行截取，用来建立数据集
_ _ _
_ _ _

### 提交情况

* 1.完成人脸检测（采用0pencv已经训练好的模型进行检测）
  ![1](https://github.com/chareneor/BS/blob/master/image/a.jpg)
_ _ _
_ _ _

* 2.完成人脸截取（未对多个人脸情况进行分析 + 增加尺寸变换 ）
  ![2](https://github.com/chareneor/BS/blob/master/image/face.jpg)
  
_ _ _
_ _ _
 * 3.整合 未完成版（将之前代码整合成函数，加入重命名函数对测试文件进行规范）
    
  

