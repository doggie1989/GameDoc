# GameDoc



支付接口：

http://apis.icoos.cn/PaymentService/makePayment?cardNum=321321321321&expireYear=20&expireMonth=11&cvv=182&userId=100001

cardNum是卡号
expireYear过期年份
expireMonth过期月份
cvv安全码
userId用户账号Id（钱是冲进这个Id的）


提现接口：

http://apis.icoos.cn/PaymentService/payouts?userId=100001&accountName=Yu YiQing&accountNum=321321321&amount=10000000

userId用户账号Id ，从这个账号提现

accountName 银行账号名字

accountNum  银行账号

accountNum 银行bsb

amount 提现数额
