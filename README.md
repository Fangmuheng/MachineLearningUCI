# MachineLearningUCI
Use machine learning to process UCI data sets

### 1.Bank Marketing Data Set

（银行销售数据集）

数据集中包含四个CSV文件，其中有：
1.bank.csv - 从bank-full中选出的10%的样例（4521个）
2.bank-full.csv - 完整样例（45211个），16个特征。（老版本）
3.bank-additional.csv - 从bank-additional-full中选出的10%的样例（4119个）
4.bank-additional-full.csv - 完整样例（41188个），20个特征

**数据分析**

20个输入特征：年龄、职务、婚姻情况、教育水平、违约记录、住房、贷款、联系人、月、一周中的最后联系人、持续时间、广告活动、本次活动中联系的次数，最后一次接触距离上一次接触的时间，以前的活动中联系的次数，上一次活动成功与否，就业变化率，消费者物价指数，消费者信心指数，欧元银行同业拆借利率，就业人数。

输出变量（期望目标）：客户是否已经订阅定期存款？

### 2.Bias correction of numerical prediction model temperature forecast Data Set

（数值型预测模型气温预测的偏差校正数据集）

1个csv文件：Bias_correction_ucl.csv

**数据分析**

| **属性名**           | **属性介绍（括号内为数据范围）**                     |
| -------------------- | ---------------------------------------------------- |
| station              | 气象站号码                                           |
| Present_Tmax         | 当前最高温（20-37.6）                                |
| Present_Tmin         | 当前最低温（11.3-29.9）                              |
| LDAPS_RHmin          | LDAPS模型预测的次日最低相对湿度（19.8-98.5）%        |
| LDAPS_RHmax          | LDAPS模型预测的次日最高相对湿度（58.9-100）%         |
| **LDAPS_Tmax_lapse** | LDAPS模型对次日最高气温的预测（17.6-38.5）           |
| **LDAPS_Tmin_lapse** | LDAPS模型对次日最低气温的预测（14.3-29.6）           |
| LDAPS_WS             | LDAPS预测次日平均风速（2.9 to 21.9）                 |
| LDAPS_LH             | LDAPS预测次日平均潜热通量（13.6 to 213.4）           |
| LDAPS_CC1            | LDAPS预测次日首六小时（0-5）时平均云量（0 to  0.97） |
| LDAPS_CC2            | 第二个六小时（6-11）（0 to  0.97）                   |
| LDAPS_CC3            | 第三个六小时（12-17）（0 to  0.98）                  |
| LDAPS_CC4            | 第四个六小时（18-23）（0 to  0.97）                  |
| LDAPS_PPT1           | LDAPS预测次日首六小时（0-5）平均降水（0 to  23.7）   |
| LDAPS_PPT2           | 第二个六小时（6-11）                                 |
| LDAPS_PPT3           | 第三个六小时（12-17）                                |
| LDAPS_PPT4           | 第四个六小时（18-23）                                |
| lat                  | 纬度（37.456-37.645）                                |
| lon                  | 经度（126.826-127.135）                              |
| DEM                  | 海拔（12.4-212.3）                                   |
| Slope                | 坡度（0.1-5.2）                                      |
| Solar radiation      | 日入射太阳辐射（4329.5 to 5992.9）                   |
| **Next_Tmax**        | 次日最高温度（17.4-38.9）                            |
| **Next_Tmin**        | 次日最低温度（11.3-29.8）                            |