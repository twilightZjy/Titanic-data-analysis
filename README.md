# 泰坦尼克号数据分析
对泰坦尼克号上2224 名乘客和 891 名船员的人口学数据和乘客基本信息进行分析，找出什么样的原因可能获得更高的生还率。

### 提出问题
首先，根据泰坦尼克号的数据，可以提出的问题有
1. 有哪些因素会让船上的人生还率更高。

### 猜想
对乘客生还率可能造成影响的因素有：  
1、性别。发生灾难事件时，大部分情况会先救援女性。变量：Sex  
2、年龄。老人和小孩有可能会有优先被救援的可能。变量：Age  
3、经济地位。经济地位越高，被救援的可能性越大。参考变量：Fare，Cabin,Pclass


#### 结论：
1、性别与此前猜想一致，女性比男性更能获得生还的可能。
2、年龄因素对生还率也有一定影响，年龄在0-8岁之间和18-35岁之间生还的可能性越大。
3、经济地位对生还率的影响非常重要，经济地位越高，生还的可能性越高。

####  不足：
数据中由于部分乘客没有记录年龄，这一部分乘客未能进行分析，故对最终结果有一定的影响。
由于泰坦尼克号事件是一系列复杂事件最终导致的结果，故本次推论存在一定的偶然性，故该推论并不能完全证明两者之间有任何相关性，仅供参考。
