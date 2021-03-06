# datasets
储存用于数据分析的数据集

## 如何直接在Python、R等直接读取数据
读取的链接需要使用原始链接，可以在GitHub的csv文件页面内点击「Raw」按钮进入原始链接，此时再复制URL则可以正常读取了

## titanic-data泰坦尼克幸存者数据集
「titanic-data」数据集是热门的泰坦尼克号幸存者数据集，用于进行机器学习的练习
| 变量名 | PassengerId | Survived                 | Pclass                                 | Name     | Sex         | Age         | SibSp                    | Parch                | Ticket   | Fare    | Cabin  | Embarked                                                      |
| -------- | ----------- | ------------------------ | -------------------------------------- | -------- | ----------- | ----------- | ------------------------ | -------------------- | -------- | ------- | ------ | ------------------------------------------------------------- |
| 变量解释 | 乘客编号 | 乘客是否存活(0=NO 1=Yes) | 乘客所在的船舱等级,(1=1st,2=2nd,3=3rd) | 乘客姓名 | 乘客性别 | 乘客年龄 | 乘客的兄弟姐妹和配偶数量 | 乘客的父母与子女数量 | 票的编号 | 票价  | 座位号 | 乘客登船码头。 C = Cherbourg; Q = Queenstown; S = Southampton |
| 数据类型 | numeric     | categorical              | categorical                            | string   | categorical | categorical | numeric                  | numeric              | string   | numeric | string | categorical                                                   |

## antweb_zh蚁网中国蚂蚁分类阶元
爬取自蚁网的分类数据，包含了常见的国内蚂蚁的分类地位

## 中国蜻蜓名录
数据来自国内的蜻蜓分类学者，共计20科，170属，689种
