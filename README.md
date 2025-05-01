# 信用卡詐欺偵測混合模型

## 專案說明
本專案旨在運用 Isolation Forest 與 XGBoost 模型進行信用卡詐欺偵測。
資料集為極度不平衡，包含正常交易與少量詐欺交易。

## 分析流程
1. 資料探索（EDA）：檢視詐欺比例與金額分佈
2. 建立 Isolation Forest 模型進行異常偵測
3. 建立 XGBoost 模型進行監督式分類
4. 評估模型性能，最終達到 F1-score 0.86

## 使用技術
- Python（pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost）
- 機器學習（異常偵測、監督式分類）

## 如何使用
1. 安裝 requirements.txt 中列出的套件
2. 開啟 `fraud_model.ipynb` 查看分析流程與結果

## 作者
黃睿翔