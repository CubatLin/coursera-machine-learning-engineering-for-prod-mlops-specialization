# 1. Chapter 1:
----
## 資料飄移有兩種狀態:
1. concept drift(x到y的映射概念已不再一樣):
    * 用房屋大小預測房價(考量通膨房價一直往上增，但房屋大小從來不變)
2. data drift(x到y的映射概念相似，但資料分布不同了):
    * 做語音辨識，但英文語法慢慢的改變(Grudual change)
    * COVID突然發生，大家改線上購買非常頻繁信卡資料突然改變劇烈(Suddenly change) -> 要馬上搜集新資料並更新模型

## 模型上線監控(metrics會一直換):
1. metrics:
    * 軟體部分: memory, compute, server load
    * input metrics: num missing value, avg input 
    * output metrics: time user switches to pick tags(可能一開始的標籤不是他要的)
2. 如果是一個model接一個model，這樣每一個model的output都要有自己的metrics






