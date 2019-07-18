# 支付宝 AliPay
支付宝内部API调用[整理]

页面上的二维码 就是这些内容

用户id是什么？
登陆后cookie里的 CLUB_ALIPAY_COM  2088432xxxxxxxxx

2019-07-18

生成收款码 金额 备注 不可修改

alipays://platformapi/startapp?appId=20000123&actionType=scan&biz_data={"s": "money","u": "用户id","a": "金额","m":"备注"} 

![image](https://raw.githubusercontent.com/24qy/alipays/master/收款码.png)

转账 金额 备注 可修改

alipays://platformapi/startapp?appId=09999988&actionType=toAccount&goBack=NO&amount=金额&userId=用户id&memo=备注 

![image](https://raw.githubusercontent.com/24qy/alipays/master/转账码.png)

