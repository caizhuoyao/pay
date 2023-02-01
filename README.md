# 有需要更加免费源码的可以联系telegram：[Cobrapay](https://t.me/Cobrapay)

## 三方四方支付系统

## 功能介绍：
本程序是基于微信、支付宝应用开发的免签支付程序,开放源代码,提供于技术人员学习与交流,本团队专注支付系统开发,版本长期迭代,故此项目后期会同步升级。
  

## 业务说明：
供码方（码商）安装本平台监控APP产收款码，支付押金给支付平台，开始收款
网站方（盘口），对接支付平台，网站方玩家充值到N个供码方。
供码方收满金额+佣金，供码方收款码自动下线。
网站方提现，供码方抢单打款给网站方，供码方开始上线收款。
功能说明：
网站方玩家充值每次会充值给不同的供码方收款（顺序轮循）
网站方提现，每次提现都由不同的供码方抢单下发打款
投诉只会投诉到供码方，平台和网站方无风险
平台不存在资金风险，通道风险和收款帐号风险
意思是供码方为了要赚钱需要先充值押金，收款码才会上线收款。网站方提现的时候供码方给网站方打款，打款后供码方开始收款。平台只作为工具回调，不存在资金过往，确保资金安全。  

## 技术说明：
基于thinkphp5，使用redis技术进行存储算法轮循规则，使用workerman作为websocket通讯技术与APP进行桥接，使用mysql作为数据库存储工具。

![image](https://github.com/caizhuoyao/pay/blob/main/img/1675234874914.jpg)
![image](https://github.com/caizhuoyao/pay/blob/main/img/1675234897357.jpg)
![image](https://github.com/caizhuoyao/pay/blob/main/img/1675234915726.jpg)
![image](https://github.com/caizhuoyao/pay/blob/main/img/1675234931444.jpg)
![image](https://github.com/caizhuoyao/pay/blob/main/img/1675234947722.jpg)
![image](https://github.com/caizhuoyao/pay/blob/main/img/1675234965562.jpg)
