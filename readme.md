# Papers

This repo contains many papers various in many high-tech areas which I mainly research for. Including *Computer Vision*, *NLP*, *Quantum* etc.

Every paper I read or stared will drop right here as well as some notes on it.



## cv

1. [Light-Head R-CNN: In Defense of Two-Stage Object Detector](https://arxiv.org/pdf/1711.07264.pdf).

   较为新的一个检测算法，对比了诸如RetinaNet，FPN，RFCN等较新的2-stage检测方法，结果显示，由于架构的不同，是的他的速度更快，号称可以达到100fps，这就牛逼了，不知道什么平台测试的。比yolo还快。

   代码已经开源：https://github.com/zengarden/light_head_rcnn.git

2. [Learning a Rotation Invariant Detector with Rotatable Bounding Box](https://github.com/liulei01/DRBox):

   这篇论文就牛逼了，直接生成不规则的矩形，这是**下一代目标检测的主要方向**, 并且，个人认为，还是很有用途，比如在一些俯视图上，或者一些不规则的物体上检测很有用。或者可以试一试用在车道线的检测上？

3. [R2CNN: Rotational Region CNN for Orientation Robust Scene Text Detection]()

   带旋转角度的矩形框检测。多用在文本检测上，在一些可以利用的场合，比如文本检测，仪表盘检测等，还是很有用的。

4. 