這個是計算獎金專案的py檔\
(有附上成品示意圖)

此專案使用 pyqt5 做出介面\
使用者(主管)可以輸入專案總金額及參與人員的參與比例\
算出每位職員當月的獎金總額

規則如下 該案接案金額5% = 該案獎金\
並依參與比例分配給職員\
主管可以額外拿到 該案接案金額1%

此程式可直接算出每位職員當月獎金\
最多可同時加入6個專案 4個職員(含主管)\
並加總向公司說明當月部門獎金狀況

Ex: 完成一個接案金額為100000的案子\
主管 員工1 員工2 員工3 都各負責25%\
100000 * 0.05 = 5000\
5000/4 = 1250\
所以主管獎金為 1250+1000 其餘3位都是1250


![image](https://github.com/Ben10225/py_bonusCalc/blob/main/python%E5%B0%88%E6%A1%88%E6%88%90%E5%93%81%E5%9C%96.png)
