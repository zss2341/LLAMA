# LLAMA
![image](https://user-images.githubusercontent.com/25265905/223897329-dbda8500-f39c-474a-a608-c93fe0b56bb6.png)


让我们从baby阶段一步步的训练自己的亚玛。第一步：先把文件上传到阿里云盘


# 第一步：下载模型
### 模型选择：
推荐依据是评测机构对于不同参数的模型进行的IQ测试：

LLaMA	Reasoning tasks
Number of parameters	BoolQ	PIQA	SIQA	HellaSwag	WinoGrande	ARC-e	ARC-c	OBQA	COPA
7B	76.5	79.8	48.9	76.1	70.1	76.7	47.6	57.2	93
13B	78.1	80.1	50.4	79.2	73	78.1	52.7	56.4	94
33B	83.1	82.3	50.4	82.8	76	81.4	57.8	58.6	92
65B	85.3	82.8	52.3	84.2	77	81.5	56	60.2	94

从上表中看，33B与65B的表现差距不大。推测该模型的最佳甜点就在33B左右甚至以下。
而7B与13B相比，则7B性价比较高。
故而推荐个人开发者训练7B的模型，中小企业训练33B的模型。

### 阿里云盘下载链接：
7B https://www.aliyundrive.com/s/26jvNPox7Ep

13B https://www.aliyundrive.com/s/DXfaAxPrbJv

30B https://www.aliyundrive.com/s/DXfaAxPrbJv

65B https://www.aliyundrive.com/s/2zcQYeTSfHJ

### 百度云盘下载链接：
7B 

13B

30B

65B

下面是该模型经过GPTQ转化而来的简化版，使用GPTQ技术能够大幅度的降低模型对于GPU显存以及内存的消耗。故而推荐指数+1

7B 

13B

30B 

65B

由于GPTQ简化版的性能会随着参数的增加而降低受益，故而推荐所有人使用30B的4Bit版本

# 第二步：平台选择

首选：谷歌colab

次选：百度飞浆

