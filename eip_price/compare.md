# EIP计费总览

对于外网弹性IP，带宽为EIP的一个属性。

计费方式|	计费规则|	收取费用|
|---|---|---|
带宽|	按照固定带宽收费。[详情](https://cms-docs.ucloudadmin.com/unet/eip/introduction?id=%e6%a0%87%e5%87%86%e5%b8%a6%e5%ae%bd)|带宽费用|
流量|	按照出向带宽所消耗的流量进行计费，每日0点结算。[详情](https://cms-docs.ucloudadmin.com/unet/eip/introduction?id=%e6%b5%81%e9%87%8f%e8%ae%a1%e8%b4%b9)|流量费用+IP费用|
带宽后付费|	按照保底+后付费收费，不足保底收取保底带宽费用，超过保底部分按照超过部分的带宽平均值收费。[详情](https://cms-docs.ucloudadmin.com/unet/eip/introduction?id=%e5%b8%a6%e5%ae%bd%e5%90%8e%e4%bb%98%e8%b4%b9)|带宽费用|
共享带宽|	多IP共享一条带宽，分别收取带宽费用和IP费用。[详情](https://cms-docs.ucloudadmin.com/unet/eip/introduction?id=%e5%85%b1%e4%ba%ab%e5%b8%a6%e5%ae%bd)|共享带宽费用+IP费用|

### 说明：
1、所购买带宽值

购买值（峰值）为出向带宽值，当出向带宽≤50M时，入向带宽=50M；当出向带宽＞50M时，入向带宽=出向带宽。

3、香港回国带宽

香港回国线路采用专用线路，购买带宽值≤2Mbps时，回内地的带宽上限为购买值；购买带宽值＞2Mbps，且≤20Mbps时，回内地带宽为2Mbps； 购买带宽值＞20Mbps时，回内地带宽限制为购买值的1/10。若需更高的香港回国带宽可购买境内到香港的[UDPN专线](https://docs.ucloud.cn/udpn/guide)。
