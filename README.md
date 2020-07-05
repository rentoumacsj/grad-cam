# grad-cam
A demo code of Grad-CAM, implemented by PyTorch.
## 使用说明：
*  预训练好的模型：放在pretrained_model中，pytorch格式，包含了分类的label；默认是pytorch官方的训练好的基于VGG19的猫狗分类模型。
注：官方模型的下载地址：https://github.com/pytorch/vision/tree/master/torchvision/models
*  配置是否启用GPU：grad-cam.py 第197行
*  配置源图片：grad-cam.py 第235行
*  配置要显示的模型（一般为卷积层最后一层）：grad-cam.py 第231行
*  配置Label（分类）：grad-cam.py 第246行
*  结果生成在results文件夹中。
