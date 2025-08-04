# SwinIR-Pytorch 代码精简版

模型的构建部分参考了github开源项目 SwinIR

[https://github.com/JingyunLiang/SwinIR](https://github.com/JingyunLiang/SwinIR)

train.py 为训练的代码(使用了Tensorboard来记录训练过程)

pred.py 为推理的代码

在ISTD测试集的结果为(反归一化后计算):

```
Average PSNR: 27.6236
Average SSIM: 0.9586
Average MSE Loss: 189.5856
Average RMSE Loss: 11.9893
```
