# LLP-ACCP-Java

欢迎来到连连账户+开放平台API接口的Java示例代码仓库， 本仓库包含示例代码及必要的说明。

## 主要内容：

本仓库中所有Demo均请求连连账户+STE环境，Demo仅做参考，请仔细阅读Demo代码，如有问题及时群内连连技术技术。

### 前置要求：
Java JDK版本为1.8及以上

### 使用说明
1、config/LLianPayContant.java 保存测试商户号、测试商户号对应私钥、连连公钥，可视情况进行替换。<br/>
2、security/LLianPayAccpSignature.java 包含签名、验签、本地加密方法。<br/>
3、client/LLianPayClient.java 发起请求方法。<br/>
4、部分Demo需要用debug打断点方式进行调试，请自行阅读注释。<br/>
5、部分Demo是无法直接运行的，需要在代码中添加相应个人信息后方可运行（手机号、证件号、银行卡号等）。<br/>

### Demo说明（持续完善中）
#### 开户：
* 页面开户：H5OpenacctDemo.java https://open.lianlianpay.com/docs/accp/accpstandard/openacct-apply.html
* 个人开户流程：IndividualOpenacctDemo.java https://open.lianlianpay.com/docs/accp/accpstandard/accp-openacct-flow.html
* 个人新增绑卡申请/验证：IndividualBindCardDemo.java https://open.lianlianpay.com/docs/accp/accpstandard/individual-bindcard-apply.html
* 个人用户信息修改：IndividualModifyUserInfoDemo.java https://open.lianlianpay.com/docs/accp/accpstandard/modify-userinfo-individual.html

#### 充值消费类：
* 统一支付创单：TradeCreateDemo.java https://open.lianlianpay.com/docs/accp/accpstandard/accp-tradecreate.html
* 余额支付+交易二次短信验证：PaymentBalanceDemo.java https://open.lianlianpay.com/docs/accp/accpstandard/payment-balance.html
* 银行卡快捷支付+交易二次短信验证：PaymentBankCardDemo.java https://open.lianlianpay.com/docs/accp/accpstandard/payment-bankcard.html
* 账户+收银台：CashierPayCreateDemo.java https://open.lianlianpay.com/docs/accp/accpstandard/accp-cashier-paycreate.html
* 支付单关单：ClosePaymentDemo.java https://open.lianlianpay.com/docs/accp/accpstandard/close-payment.html

#### 提现：
* 提现申请：WithDrawalDemo.java https://open.lianlianpay.com/docs/accp/accpstandard/withdrawal.html

#### 公共API：
* 随机因子获取：GetRandomDemo.java https://open.lianlianpay.com/docs/accp/accpstandard/get-random.html
* 大额行号查询：QueryCnapsCodeDemo.java https://open.lianlianpay.com/docs/accp/accpstandard/query-cnapscode.html
* 申请密码控件Token：ApplyPasswordElementDemo.java https://open.lianlianpay.com/docs/accp/accpstandard/apply-password-element.html

#### 账户管理类：
* 用户信息查询：QueryUserInfoDemo.java https://open.lianlianpay.com/docs/accp/accpstandard/query-userinfo.html
* 资金流水列表查询：QueryAcctserialDemo.java https://open.lianlianpay.com/docs/accp/accpstandard/query-acctserial.html
* 资金流水详情查询：QueryAcctserialDetailDemo.java https://open.lianlianpay.com/docs/accp/accpstandard/query-acctserialdetail.html





















