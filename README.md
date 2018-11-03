# 第一阶段：单模型训练
## 庞鸿宇负责部分   
接下来训练的是：  
已经训练完成的结果：

| 模型 | 模型大小 | 图片增强方式 | 训练集loss | 验证集loss | 验证集acc | 模型文件名 |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| resnet-18  | 46.8  | 有颜色   | 0.30824 | 0.37186 | 0.860 | resnet-18-1.pth  |
| resnet-18  | 46.8  | 无颜色   | 0.22341 | 0.34586 | 0.876 | resnet-18-2.pth  |
| resnet-18(30°) | 46.8  | 无颜色 | 0.19064 | 0.34471 | 0.874 | resnet18-again.pth |
| resnet-34  |       | 无颜色   | 0.22789 | 0.34120 | 0.872 | resnet-34-0.pth  |
| resnet-34(30°) |       | 无颜色 | 0.18196 | 0.34425 | 0.874 | resnet34-2.pth     |
| resnet-34(30°) |       | 无颜色 | 0.21181 | 0.32807 | 0.875 | resnet34-1.pth     |
| resnet-50  | 102.5 | 无颜色   | 0.25836 | 0.36276 | 0.869 | resnet-50-1.pth  |
| resnet-50(30°) | 102.5 | 无颜色 | 0.22288 | 0.34026 | 0.877 | resnet50-2.pth     |
| resnet-101 |       | 无颜色   | 0.20078 | 0.34351 | 0.877 | resnet-101-0.pth |
 resnet-101(30°) |       | 无颜色 | 0.21259 | 0.33527 | 0.877 | resnet101-2.pth    |
| resnet-152 | 241.5 | 无颜色   | 0.22513 | 0.37924 | 0.864 | resnet-152-0.pth |
|            |       | 无颜色   | 0.      | 0.      | 0.    |                  |
|            |       | 无颜色   | 0.      | 0.      | 0.    |                  |
|            |       | 无颜色   | 0.      | 0.      | 0.    |                  |  

   
     
## 刘世望负责部分   
接下来训练的是：  
已经训练完成的结果：

| 模型 | 模型大小 | 图片增强方式 | 训练集loss | 验证集loss | 验证集acc | 模型文件名|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| densenet121  |       28.6      |      无颜色       |      0.21019     |      0.34024      |      0.876     |     densenet121.pth      |
| densenet161  |       107.5      |      无颜色       |      0.21318     |     0.34413       |     0.873    |densenet161.pth     |
| densenet161  |       107.5       |       有颜色     |           |            |     0.863    |       densenet161_c.pth    |
| densenet201  |      74       |      无颜色       |     0.17030      |     0.34118       |     0.876      |      densenet201.pth     |
| densenet201  |              |      有颜色      |           |            |     0.859      |           |
| inceptionresnetv2  |      218.1       |     无颜色       |     0.23690      |      0.35496      |       0.863    |    inceptionresnetv2.pth       |
| inceptionresnetv2  |              |    有颜色        |           |            |     0.861      |           |
| inceptionv4  |      165.4       |      无颜色       |     0.26048      |      0.35276      |      0.870     |     inception4.pth      |
| inceptionv4  |      165.4       |      有颜色       |           |            |     0.861      |    inception4_c.pth       |
| nasnetmobile  |      17.6       |     无颜色      |     0.26444     |     0.36026     |     0.861     |   nasnetmobile.pth     |
|  senet154   |   453.9    | 无颜色   | 0.16924      | 0.36131      | 0.865    |        senet154.pth          |
|      se_resnet50      |    104.9   | 无颜色   | 0.22028      | 0.33347      | 0.874    |     se_resnet50.pth          |
|      se_resnext50_32x4d      |   102    | 无颜色   | 0.21120      | 0.35766      | 0.869    |       se_resnext50_32x4d.pth            |  
|     se_resnet101       |    190.2   | 无颜色   | 0.22037      | 0.34053      | 0.876    |        se_resnet101.pth           |
|            |       | 无颜色   | 0.      | 0.      | 0.    |                  |
|            |       | 无颜色   | 0.      | 0.      | 0.    |                  | 
# 第二阶段：模型融合测试
# 第三阶段：模型改进
