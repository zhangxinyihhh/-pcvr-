

# -pcvr-
a榜78，b榜前6%代码
参加了天池的广告商品转化率预估，由于设备问题，弃了决赛。。。。
供上初赛代码：

1.datasplit：用滑窗法划分数据集

2.catrgory——fillna：处理商品种类

3.property_fillna：处理商品属性

4.category_fenduan：

5.pre_fillna注意is_trade：缺失值填充

6.shop_fenduan：连续值离散化

7.leakfeature1：统计label中间隔等特征

8.leakfeature2：统计label中购买率等特征

9.feature_with_time：按天组合特征

10.xgb_model：用xgb进行训练预测
