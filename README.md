# 飞浆的坑和解决办法

#### AssertionError: Bad argument number for Assign: 2, expecting 3[^1]
问题描述：存储模型时报错，`AssertionError: Bad argument number for Assign: 2, expecting 3`。
环境：macOS, python3.8, padhle 2.1
原因：gast库版本高
解决办法：把gast卸载，重新安装0.3.3版本。`pip uninstall gast, pip install gast==0.3.3`。



*参考资料*
[^1 ]: [PaddleDetection 导出PP-YOLO 类型模型时报错AssertionError: Bad argument number for Assign: 2, expecting 3 解决记录](https://www.cnblogs.com/GengMingYan/p/14955474.html) 
