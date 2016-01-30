# VoicePrint

## 1. 程序说明

VoicePrint ([算法原理说明点我](http://blog.csdn.net/c395565746c/article/details/6210920)) 是一款基于高斯混合模型的文本无关的声纹识别算法验证程序



VoicePrint的特点是：
 
- 语音特征向量：采用 MFCC系数（梅尔倒谱系数）
- 模式匹配模型：采用 GMM 模型（高斯混合模型）
	
## 2. 最近更新

**VoicePrint V1.1正式版**

- 修复建模、识别过程中间语音转储临时文件可能无法删除。
- 修改语音段数由 3 改为 4，每段语音改为定长的 50 帧。
- GMM模型数据转储文件结构微调，不再兼容 V1.1 以前的版本。

**VoicePrint V1.0**

- 增加了将 GMM 模型数据导出为文件的功能，并能把文件导入程序。
- 修改了识别范围值。
- 修改了声纹识别算法，改为动态数组分配内存。

## 3. 温馨提醒

本程序为课程实验验证开发，所实现的声纹识别算法难免有错误及不妥之处！
   
提醒：因为本程序是简略的验证程序，建议不要在正式项目中直接使用本程序中的声纹识别代码。

### TODO: 

- 音量归一化（暂无，提高识别率）
- 去除背景噪声（暂无，提高识别率）
- iOS Demo（2016年）
- 英文注释及 README（2016年）

## 4. 贡献者

- [Dake](https://github.com/dake/)

**如果觉得这个项目有用，请我喝杯咖啡吧：**

- 支付宝钱包扫码：

![alipay](8366834390131826-3.png)
