# Similarity-martix
**惡意程式的相似度矩陣**
## 使用
* Binary字串分析
* Jaccard Similarity
* NetworkX
## 特點
* 數值越高，判斷標準越高 (**正比**)
* 判斷標準越高，關聯線的數量越少 (**反比**)
###### 範例如下圖(0.3與0.9)
![GITHUB](https://github.com/PudiHero/Similarity-martix/blob/main/threshold_03_09.jpg)
想必各位已經看出了其中的端倪，0.3較0.9更多線，也就是**更有關聯性**。
這句話幾乎解讀出了問題的根本，若能理解透徹核心原理，對其就有了一定的了解程度。
關聯似乎是一種巧合，但如果我們從一個更大的角度看待問題，這似乎是一種不可避免的事實。
![GITHUB](https://i.imgur.com/Plrg3d1.png)
