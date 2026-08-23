# [Contribute to PaddleDetection] Yes, PP-YOLOE! 基于PP-YOLOE的算法开发

本期活动联系人：[thinkthinking](https://github.com/thinkthinking)

## 建设目标
[PP-YOLOE+](../../configs/ppyoloe)是百度飞桨团队开源的最新SOTA通用检测模型，COCO数据集精度达54.7mAP，其L版本相比YOLOv7精度提升1.9%，V100端到端(包含前后处理)推理速度达42.2FPS。

我们鼓励大家基于PP-YOLOE去做新的算法开发，比如：

- 改造PP-YOLOE适用于旋转框、小目标、关键点检测、实例分割等场景；
- 精调PP-YOLOE用于工业质检、火灾检测、垃圾检测等垂类场景；  
- 将PP-YOLOE用于PP-Human、PP-Vehicle等Pipeline中，提升pipeline的检测效果。

相信通过这些活动，大家可以对PP-YOLOE的细节有更深刻的理解，对业务场景的应用也可以做更细节的适配。

## 参与方式

- **方式一**：**列表选题**，见招募列表（提供了选题方向、题目、优秀的对标项目、文章和代码，以供学习）。
- **方式二**：**自选题目**，对于非参考列表内的题目，可自主命题，需要与负责人 [thinkthinking](https://github.com/thinkthinking)讨论后决定题目。

## 题目认领

为避免重复选题、知晓任务状态、方便统计管理，请根据如下操作认领您的题目。

在本issue提交题目:[issue](https://github.com/PaddlePaddle/PaddleDetection/issues/7345)  

* 方式一（列表选题）：在“招募列表”中选择题目，并在[issue](https://github.com/PaddlePaddle/PaddleDetection/issues/7345)中，回复下列信息：
```

【列表选题】
编号：XX
题目：XXXX
认领人：XX
```

* 方式二（自选题目）：自主命题，直接在 [issue](https://github.com/PaddlePaddle/PaddleDetection/issues/7345) 中，回复下列信息：

```
【自选题目】
题目：XXXX
认领人：XX
```

## 招募列表

| 序号 | 类型     | 题目                        | 难度 | 参考                                                                              | 认领人 |
| :--- | :------- | :-------------------------- | :--- | :-------------------------------------------------------------------------------- | :----- |
| 01   | 模型改造 | PP-YOLOE用于旋转框检测      | 高   | https://github.com/PaddlePaddle/PaddleDetection/tree/release/2.5/configs/rotate   | ----   |
| 02   | 模型改造 | PP-YOLOE用于小目标检测      | 高   | https://github.com/PaddlePaddle/PaddleDetection/tree/release/2.5/configs/smalldet | ----   |
| 03   | 模型改造 | PP-YOLOE用于关键点检测      | 高   | https://github.com/WongKinYiu/yolov7/tree/pose                                    | ----   |
| 04   | 模型改造 | PP-YOLOE用于实例分割        | 高   | https://github.com/WongKinYiu/yolov7/tree/mask                                    | ----   |
| 05   | 垂类应用 | 基于PP-YOLOE的缺陷检测      | 中   | https://aistudio.baidu.com/aistudio/projectdetail/2367089                         | ----   |
| 06   | 垂类应用 | 基于PP-YOLOE的行为检测      | 中   | https://aistudio.baidu.com/aistudio/projectdetail/2500639                         | ----   |
| 07   | 垂类应用 | 基于PP-YOLOE的异物检测      | 中   | https://aistudio.baidu.com/aistudio/projectdetail/3846170?channelType=0&channel=0 | ----   |
| 08   | 垂类应用 | 基于PP-YOLOE的安全监测      | 中   | https://aistudio.baidu.com/aistudio/projectdetail/2503301?channelType=0&channel=0 | ----   |
| 09   | Pipeline | PP-YOLOE-->PP-Human大升级   | 中   | https://aistudio.baidu.com/aistudio/projectdetail/4606001                         | ----   |
| 10   | Pipeline | PP-YOLOE-->PP-Vehicle大升级 | 中   | https://aistudio.baidu.com/aistudio/projectdetail/4512254                         | ----   |


 <mark>【注意】招募列表外的，欢迎开发者联系活动负责人[thinkthinking](https://github.com/thinkthinking)提交贡献👏 <mark>

## 贡献指南

1. 提ISSUE、PR的步骤请参考[飞桨官网-贡献指南-代码贡献流程](https://www.paddlepaddle.org.cn/documentation/docs/zh/develop/dev_guides/code_contributing_path_cn.html)
2. AI-Studio使用指南请参考[AI-Studio新手指南](https://ai.baidu.com/ai-doc/AISTUDIO/Tk39ty6ho)

## 原则及注意事项
1. <u>需</u>使用PaddlePaddle框架, 建议复用PaddleDetection代码。
2. <u>建议使用</u>[Paddle框架最新版本](https://www.paddlepaddle.org.cn/).
3. <u>PR</u>需提到[PaddleDetection-develop](https://github.com/PaddlePaddle/PaddleDetection/tree/develop)分支。
4. 模型改造类的任务建议以<u>PR形式</u>提交
5. 垂类应用以及Pipeline类的任务建议以<u>AI-Studio项目形式</u>提交，项目会同步到[产业范例页面](https://github.com/PaddlePaddle/PaddleDetection/blob/develop/industrial_tutorial/README.md)

## 还有不清楚的问题

欢迎大家随时在本[issue](https://github.com/PaddlePaddle/PaddleDetection/issues/7345)下提问，飞桨会有专门的管理员进行疑问解答。

有任何问题，请联系本期活动联系人 [thinkthinking](https://github.com/thinkthinking)

非常感谢大家为飞桨贡献！共建飞桨繁荣社区！
