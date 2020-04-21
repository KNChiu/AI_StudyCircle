
# Loss Function (損失函數)

## 最小化：    
在理想的模型中，我們希望預測值和實際值是相等的，但現實應用中預測值和實際值是有落差的    
而之間所謂的落差在統計上稱為殘差(residual)，實際應用上我們會希望殘差越小越好。

` loss/residual = y - ŷ `

損失/殘差、y 表示實際值、 ŷ 表示預測值

## 回歸：    
機器學習中最常被用在回歸上的損失函數：    
因為預測值和實際值的差值有正負，所以不能直接相加，常見的方法有將差值平方變成正數、用絕對值讓差值變成正數

### 均方誤差(Mean square error，MSE)：       
     預測值與真實值之間差異的均方值   
公式：

![image](https://github.com/KNChiu/AI_StudyCircle/blob/master/Picture/MSE_formula.png)

例子：    
`y1 = 0, y2 = 1, ŷ1 = 100, ŷ2 = -99`

![image](https://github.com/KNChiu/AI_StudyCircle/blob/master/Picture/MSE_examples.png)

### 平均絕對值誤差(Mean absolute error，MAE)：    
    預測值與真實值之間差異的絕對值




### 參考資料：[Tommy Huang 機器/深度學習: 基礎介紹-損失函數(loss function) ](https://medium.com/@chih.sheng.huang821/%E6%A9%9F%E5%99%A8-%E6%B7%B1%E5%BA%A6%E5%AD%B8%E7%BF%92-%E5%9F%BA%E7%A4%8E%E4%BB%8B%E7%B4%B9-%E6%90%8D%E5%A4%B1%E5%87%BD%E6%95%B8-loss-function-2dcac5ebb6cb "機器/深度學習: 基礎介紹-損失函數(loss function)")
