# 业绩归因 - Brinson模型

## 单期Brinson模型

单期Brinson模型，即BHB模型，认为一个时期的投资组合收益可以分为四个部分：

- 资产配置收益（Aocation Return）=Q2-Q1

- 个股选择收益（Selection Return）=Q3-Q1

- 交互收益（Interaction Return）=Q4-Q3-Q2+Q1

- 总超额收益(Total Return)=Q4-Q1

- 另外，需要计算的还有一个总超额收益（Total Return）

在计算以上几个部分之前，首先要构建四个组合：

- Q1：基准组合=各（基准资产权重*基准资产收益）之和

- Q2：积极资产配置组合=各（组合资产权重*基准资产收益）之和

- Q3：积极股票选择组合=各（基准资产权重*组合资产收益）之和

- Q4：实际组合=各（组合资产权重*组合资产收益）之和

其表述见下图：

![image](http://g.hiphotos.baidu.com/news/w%3D638/sign=0e43eeddaa4bd11304cdb43162aea488/b21bb051f8198618f0ace52a4ded2e738ad4e6b1.jpg)

两者差异在于，AR强调超额资产配置收益来源于对上涨的资产类别（比如行业i）的超配，或对下跌资产类别的低配，但AR'（BF模型）强调对涨幅超过基准总收益的类别超配，或对跌幅超过基准总收益的类别低配，更贴近现实。同时，这样修改的原因也是因为DamienLaker(2002年)发现Brinson模型中有关资产配置归因的定义在某些情况下可能会带来错误的结果。

BHB模型、BF模型都是假设基金组合的投资经理是通过Top-down的方法做出投资决策，即先决定资产配置(AR)，而后决定个股选择(SR)，但是交互收益(IR)反映的是资产配置与个股选择的联合作用，投资经理难以根据该收益做出投资决策，因此部分研究人员认为交互收益应归入个股选择收益中去，即个股选择收益重新定义为：

![image](http://e.hiphotos.baidu.com/news/w%3D638/sign=7b7446af0d55b3199cf981767ba88286/9f2f070828381f303d938707ae014c086f06f092.jpg)

## 多期Brinson模型

由于我们的绩效评估是按照月度、季度、年度来考评，这需要将单期Brinson模型推广至多期。基金组合、基准组合多期累计收益可如下计算：

![image](http://f.hiphotos.baidu.com/news/w%3D638/sign=ac8635cbb419ebc4c078759aba27cf79/060828381f30e9246d2e969f4b086e061c95f792.jpg)

但多期的超额收益并不为各期超额收益总和，即：

![image](http://g.hiphotos.baidu.com/news/w%3D638/sign=dce28c87ecc4b7453494b415f7fd1e78/29381f30e924b8997fb6739669061d950b7bf692.jpg)

为保证基金组合层面的多期归因分析可以满足公式（10），同时将分析拓展到各资产层面，将多期Brinson中的每个组合做如下修改：

![image](http://c.hiphotos.baidu.com/news/w%3D638/sign=aa26c8a8a8c379317d68852ad3c5b784/86d6277f9e2f0708faee20aeee24b899a801f2b1.jpg)

从而按照BF模型，多期行业资产配置、多期个股选择以及交互收益分别为：

![image](http://b.hiphotos.baidu.com/news/w%3D638/sign=50e58c409b82d158bb825ab2b80b19d5/bba1cd11728b471038fef762c4cec3fdfd03234e.jpg)

通过这种方法，将该基金组合细分到行业、个股层面，可以求出行业、个股对该基金多期收益的收益贡献，即：

![image](http://d.hiphotos.baidu.com/news/w%3D638/sign=1f49eec6cbbf6c81f7372feb843fb1d7/738b4710b912c8fc4005fc63fb039245d78821ad.jpg)

## 参考

[基金绩效归因分析的Brinson模型](https://baijia.baidu.com/s?old_id=407637)

[基金的投资绩效归因分析及实证研究](https://wenku.baidu.com/view/c8c36af9700abb68a982fbc2.html)这篇可以重点关注下

[基金业绩归因3：单期Brinson绩效分解模型](http://myfof.org/thread-191-1-1.html)

[基金业绩归因1：在FOF风生水起的时代，咱也谈谈基金业绩归因](http://myfof.org/thread-53-1-1.html)

[谁能介绍下基金的brinson 业绩归因模型 ？](https://www.zhihu.com/question/22839335)

[Brinson模型——债券组合绩效归因方法](https://wenku.baidu.com/view/beaf42dd168884868662d65e.html)

