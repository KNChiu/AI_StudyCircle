## Standardization (標準化)    
將數據轉化爲均值爲零，而方差爲一的標準正態分佈（高斯分佈）。

## Normalization (正規化)    
將原始資料的數據按比例縮放於 [0, 1] 區間中，且不改變其原本分佈。 

* 原始資料：    
![image](https://github.com/KNChiu/AI_StudyCircle/blob/master/Picture/w10/None.png)    

* 正規化後：    
![image](https://github.com/KNChiu/AI_StudyCircle/blob/master/Picture/w10/Normalization.png)


## 優點：
* 提升模型的收斂速度
* 提高模型的精準度

## Scale (零均值單位方差)
* 將所有特徵數據縮放成平均為0、平方差為1    
![image](https://github.com/KNChiu/AI_StudyCircle/blob/master/Picture/w10/scale.png)

## StandardScaler(平均值和標準差)
* 刪除平均值和縮放到單位方差來標準化    
![image](https://github.com/KNChiu/AI_StudyCircle/blob/master/Picture/w10/StandardScaler.png)

## MinMaxScaler(最小最大值標準化)
* 將特徵數據按比例縮放到自訂範圍    
![image](https://github.com/KNChiu/AI_StudyCircle/blob/master/Picture/w10/minmaxscale.png)

## 比較
* 嘗試分別訓練100次後比較準確度    
![image](https://github.com/KNChiu/AI_StudyCircle/blob/master/Picture/w10/Compare.png)
* 這個圖表不代表標準化方式的優劣，只能表示在這個模型中較適合的方式。
