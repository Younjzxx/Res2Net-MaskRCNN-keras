# Res2Net-MaskRCNN-keras

将原生keras版本的MaskRCNN的ResNet的模块修改为了Res2Net.

使用方法：直接将model.py文件复制到原生keras版本的MaskRCNN实现中，原项目地址如下：

https://github.com/matterport/Mask_RCNN

将mrcnn/model.py替换即可 或者直接复制我的model中的conv_block函数代码片段替换掉原来的函数。
