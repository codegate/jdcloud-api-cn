# 修改实例模板

## 前置条件

对于已经创建的高可用组，其新增云主机将按照当前关联的实例模板配置信息创建，若由于您业务的调整导致需要修改新增云主机的配置信息，您可以通过修改高可用组关联的实例模板实现。需要注意的是，修改前后的实例模板所配置的私有网络需要一致，且配置实例规格为第二代云主机规格。


## 操作步骤

1. 访问[高可用组控制台](https://cns-console.jdcloud.com/availabilitygroup/list)，即进入高可用组列表页面。或访问[京东云控制台](https://console.jdcloud.com)点击左侧导航栏【弹性计算】-【高可用组】进入高可用组列表页。
2. 选择地域。
3. 选择需要操作的高可用组的地域，点击名称进入其详情页。
4. 点击【资源信息Tab】-【实例模板】后方【修改】icon。
5. 在弹出修改弹窗的实例模板下拉框内将显示满足条件（私有网络相同且配置的第二代云主机规格或GPU规格）的实例模板，选择您需要更换的实例模板。
6. 点击【确定】触发修改实例模板，修改完成后弹窗将关闭并回到详情页。
