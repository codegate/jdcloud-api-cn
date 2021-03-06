# 计费概述

京东云微服务平台（JDSF）针对命名空间、调用链分析服务、微服务网关分别计费，价格与所选择的服务的规格相关。对不同的用户需求提供按配置计费和包年包月计费。

##  计费规则

- 按配置计费：

	- 该方式为按资源的实际使用计费。
	
	- 开通说明：为保证您的正常使用，开通按配置计费时您的账户余额不得少于50元。如账户金额少于50元，需充值后方可使用。
	
	- 付费模式：采用先使用后付费方式，每天凌晨，按资源配置及实际使用时长生成前一天账单并结算费用。

	- 更多信息请参考： [后付费计费说明](../../../Finance/Billing/Billing-method/Postpay.md)。

- 包年包月计费：

	- 该方式为提前支付数月或数年的费用。目前购买时间段支持1个月~9个月、1年、2年、3年；费用在您创建时一次性扣除；

	- 为了保障您的使用权益，包年包月的资源在到期前不支持执行删除操作；
	
	- 采用预付费方式，包年包月计费订单的到期时间为订单开始时间当日起向后第N个自然月或自然年的 23:59:59；
		
	- 更多信息请参考： [预付费计费说明](../../../Finance/Billing/Billing-method/Prepay.md)。		
	
**说明**

-  本产品价格不包含用户使用京东云上云主机等 IaaS 层云资源的费用。

-  当客户端通过API网关调用时，API网关将按照API调用次数收取费用。详细收费规则可参考: [API网关产品计费说明](../../API-Gateway/Pricing/Billing-Rules.md)  。

-  配置管理服务依托注册中心，使用免费。



## 续费规则

- 按配置计费续费：用户可选择将按配置的计费方式转为包年包月。操作过程可参考：[续费管理](../../../Finance/Online-Buying/Renew-Management.md)  。

- 包年包月续费：延长包年包月的使用时长。如在资源到期前续费，则新订单的开始时间为原订单的到期时间。如您在到期后续费，则新订单的开始时间为续费当天。

- 批量续费：对多个资源进行批量续费，根据用户所选续费时长，延长选中资源的使用时长。

- 如需调整“自动续费”方式，可在“续费管理”中进行操作。入口：费用>续费管理>微服务平台，然后在资源列表的“操作”中，进行“自动续费”方式的转变。


<br>

## 价格总览

### 命名空间价格说明
基础版 
| 规格阶梯 |  按配置 （元/时） | 包年包月 （元/月） | 
| :- | :- | :- |
| 1-80      | 1.8 | 920 |
| 81-200    | 2.8 | 1431 | 
| 201-500   | 4.2 | 2146| 
| 501-1000  | 7.6 | 3884| 
| 1001-1500 | 9.8  | 5008 | 


### 调用链分析服务价格说明

| 规格阶梯（TPS） |  按配置 （元/时） | 包年包月 （元/月） |
| :- | :- | :- |
| 1-300     | 1.8 | 920 |
| 301-600   | 2.6 | 1329 |	
| 601-1000  | 4.8 | 2453 |	
| 1001-1500 | 5.8 | 2964 |		


#### 微服务网关服务价格说明

| 规格阶梯（QPS） |  按配置 （元/时） | 包年包月 （元/月） |
| :- | :- | :- |
| 1-1500     | 1 | 511 |
| 1501-3000   | 2 | 1022 |	


	

## 公测说明

公测时间：2018年12月31 至 2019年12月30日

-  公测阶段，所有服务完全免费。

-  微服务网关，根据QPS规格计费，公测期间QPS在3000以下可免费使用。

-  公测结束后，命名空间都将按照 **基础版** 价格进行约束和收费。  


	
		
