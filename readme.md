
# 液奶品类优惠券使用预测  

## 项目简介  
本项目旨在通过分析顾客的历史消费数据和优惠券核销行为，构建预测模型以识别高概率核销优惠券的顾客群体，从而实现精准营销。  

## 数据说明   
数据包含以下字段：  
- **Accepted**：是否核销优惠券（目标变量，1=已核销，0=未核销）  
- **Sex**：性别（1=女，2=男）  
- **Age**：年龄段（1=中青年，2=中老年）  
- **Class**：液奶品类（1=低端，2=中档，3=高端）  
- **AvgSpending**：平均消费额  

## 功能与方法  
1. **数据预处理**：缺失值处理、异常值检测、样本均衡性分析。  
2. **模型优化**：  
   - CART决策树优化  
   - 随机森林优化  
   - XGBoost优化  
   - 逻辑回归优化  
   - 混合模型（投票机制）优化  
3. **性能评估**：通过准确率、精确率、召回率、F1分数和AUC值评估模型性能。  


# Milk Coupon Redemption Prediction

## Project Overview
This project aims to identify customer groups with a high probability of redeeming coupons by analyzing historical purchase data and coupon redemption behavior, enabling targeted marketing.

## Data Description
The dataset includes the following fields:
- **Accepted**: Coupon redemption status (target variable, 1=Redeemed, 0=Not Redeemed)
- **Sex**: Gender (1=Female, 2=Male)
- **Age**: Age group (1=Middle-aged and Young, 2=Middle-aged and Elderly)
- **Class**: Milk product class (1=Low-end, 2=Mid-range, 3=High-end)
- **AvgSpending**: Average spending amount

## Features and Methods
1. **Data Preprocessing**:
   - Missing value handling
   - Outlier detection
   - Class imbalance analysis
2. **Model Optimization**:
   - **CART Decision Tree Optimization**
   - **Random Forest Optimization**
   - **XGBoost Optimization**
   - **Logistic Regression Optimization**
   - **Ensemble Model Optimization** using voting mechanisms
3. **Performance Evaluation**:
   - Model performance assessment using accuracy, precision, recall, F1-score, and AUC values