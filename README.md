# RiskUser
JData上基于移动网络通讯行为的风险用户识别数据挖掘竞赛相关代码

## About Code
本次竞赛是在[TA的代码](https://github.com/Hanszhuang/mobileRiskUser)的基础上进行改进，虽然没能够取得很大的提升，
但是在竞赛的过程中学到了相当多的关于数据挖掘的知识，对Python的使用也有了更多的了解。在本次实训中真的收获良多。

### feature.ipynb
特征工程文件（在TA的baseline的基础上进行修改）

### TreeModel.ipynb(最终使用)
使用lightGBM进行模型训练（在TA的baseline的基础上进行修改）
降低了阈值后有效提高了预测正确率。最后达到了0.78。

### models.ipynb
参考了TA给的《数据挖掘实训入门教程》文件。

使用二层模型进行训练的一次实验。但是参数没有调好，最终结果大概是0.68左右。

不过可以明显看出来使用树模型比使用线性模型的正确率高不少。

### xgboost.ipynb
使用xgboost进行模型训练，曾经的调参代码放在了test.ipynb中，不过调参调得挺失败的，最高0.73左右。
