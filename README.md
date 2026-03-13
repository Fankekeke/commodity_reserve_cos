### 基于SpringBoot + Vue的商品进销存系统.

库存管理、仓储协同平台

###### 管理员：
公告管理 、商品管理 、库存统计 、物流信息 、订单详情 、订单评价 、订单信息 、缴费记录 、仓库管理 、仓库库存 、员工管理 、客户管理 、数据统计 、销售排行 、管理员管理 、供应采购 、供应商管理 、商品申请 、商品采购 、库房预警 、销售统计 、采购物流。

###### 用户：
账户注册登录、我的信息 、我的订单 、缴费记录 、订单评价 、商品采购 、在线支付 、商品申请。

##### 采购供应链管理
###### 供应采购/申请： 实现从商品采购申请到订单下达的全流程管控，确保货源补给及时且合规。

###### 供应商/采购物流： 维护供应商档案并实时追踪采购物资的运输状态，保障原材料或商品供应稳定。

###### 商品申请/审批： 用户提交商品需求，管理员进行审核并调拨资源，满足企业或个人定制化采购需求。

##### 仓库与库存管控
###### 仓库管理/库存： 数字化管理多级仓库，实时监控商品在库详情，实现资产存量的精细化盘点。

###### 库房预警/统计： 自动监控库存水位，针对低库存或积压品发送告警，通过数据分析优化备货策略。

###### 出入库详情： 记录每一件商品的操作流水，确保货物进出记录可查可溯，防止物资流失或账实不符。

##### 销售交易与订单体系
###### 订单信息/详情： 全程记录订单从创建、发货到完成的各阶段数据，提供多维度的交易进度查询。

###### 在线支付/缴费： 整合便捷的结算通道，自动记录缴费流水，确保销售回款及时、账目清晰。

###### 订单评价/反馈： 收集用户对商品质量及物流服务的真实评分，作为平台质量改进与信誉考核的依据。

##### 经营决策与销售看板
###### 销售统计/排行： 自动汇总销售数据，实时生成热销商品排行，辅助管理者快速调整市场经营策略。

###### 数据统计/报表： 聚合进销存全链路指标，通过可视化看板直观展示企业盈亏及业务增长趋势。

##### 人力资源与基础运维
###### 用户/员工管理： 统一管控客户关系与职员档案，通过权限设置确保不同角色在系统中的操作安全。

###### 管理员/公告管理： 维护系统后台账户安全，实时发布政策调整或促销信息，确保内部信息高效传递。

#### 安装环境

JAVA 环境 

Node.js环境 [https://nodejs.org/en/] 选择14.17

Yarn 打开cmd， 输入npm install -g yarn !!!必须安装完毕nodejs

Mysql 数据库 [https://blog.csdn.net/qq_40303031/article/details/88935262] 一定要把账户和密码记住

redis

Idea 编译器 [https://blog.csdn.net/weixin_44505194/article/details/104452880]

WebStorm OR VScode 编译器 [https://www.jianshu.com/p/d63b5bae9dff]

#### 采用技术及功能

后端：SpringBoot、MybatisPlus、MySQL、Redis、
前端：Vue、Apex、Antd、Axios

平台前端：vue(框架) + vuex(全局缓存) + rue-router(路由) + axios(请求插件) + apex(图表)  + antd-ui(ui组件)

平台后台：springboot(框架) + redis(缓存中间件) + shiro(权限中间件) + mybatisplus(orm) + restful风格接口 + mysql(数据库)

开发环境：windows10 or windows7 ， vscode or webstorm ， idea + lambok


#### 前台启动方式
安装所需文件 yarn install 
运行 yarn run dev

#### 默认后台账户密码
[管理员]
admin
1234qwer

[药店]
fank
1234qwer

#### 项目截图
暂无

|  |  |
|---------------------|---------------------|
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/f8bfd2b5-597b-41b0-8c47-86eb682e6b8d.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/9c6fa76e-fe37-4175-b720-961630edcf38.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/ea64b8ef-77b4-4984-9494-956c458cccab.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/7dc0de7d-1996-40e5-acdc-b610379bbdbf.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/e4a861ca-c643-4e25-ab72-b9c0189ef8f5.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/6b43399b-1091-4198-a50d-068db321cf80.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/d057d7d1-3827-4ccb-a57a-c1e8a1f5bcbc.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/6b57cd2c-f85a-4c8d-b9d7-9fdde269eeba.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/c890b7d7-6f2b-4b9e-b745-64ac55da8fb8.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/4ea1f528-778b-4e70-bbe7-77857bdcbc68.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/ab12a016-fa34-418c-8b58-44b5f922ec54.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/02b6ad42-3c8f-46fa-9bf3-918eadb6a312.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/a87c892a-e5ed-44a7-95e8-13bcfbb932d5.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1f9801dd-b8ce-4c58-a415-b57c220bd3e7.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/485713e4-ca5d-4db7-b690-77bd1694c334.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/f09ca0ba-f1bc-4e3f-914d-d3958b9b9aaf.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/work/936e9baf53eb9a217af4f89c616dc19.png) |

#### 演示视频

暂无

#### 获取方式

Email: fan1ke2ke@gmail.com

WeChat: `Storm_Berserker`

`附带部署与讲解服务，因为要恰饭资源非免费，伸手党勿扰，谢谢理解😭`

> 1.项目纯原创，不做二手贩子 2.一次购买终身有效 3.项目讲解持续到答辩结束 4.非常负责的答辩指导 5.**黑奴价格**

> 项目部署调试不好包退！功能逻辑没讲明白包退！

#### 其它资源

[2025年-答辩顺利通过-客户评价🍜](https://berserker287.github.io/2025/06/18/2025%E5%B9%B4%E7%AD%94%E8%BE%A9%E9%A1%BA%E5%88%A9%E9%80%9A%E8%BF%87/)

[2024年-答辩顺利通过-客户评价👻](https://berserker287.github.io/2024/06/06/2024%E5%B9%B4%E7%AD%94%E8%BE%A9%E9%A1%BA%E5%88%A9%E9%80%9A%E8%BF%87/)

[2023年-答辩顺利通过-客户评价🐢](https://berserker287.github.io/2023/06/14/2023%E5%B9%B4%E7%AD%94%E8%BE%A9%E9%A1%BA%E5%88%A9%E9%80%9A%E8%BF%87/)

[2022年-答辩通过率100%-客户评价🐣](https://berserker287.github.io/2022/05/25/%E9%A1%B9%E7%9B%AE%E4%BA%A4%E6%98%93%E8%AE%B0%E5%BD%95/)

[毕业答辩导师提问的高频问题](https://berserker287.github.io/2023/06/13/%E6%AF%95%E4%B8%9A%E7%AD%94%E8%BE%A9%E5%AF%BC%E5%B8%88%E6%8F%90%E9%97%AE%E7%9A%84%E9%AB%98%E9%A2%91%E9%97%AE%E9%A2%98/)

[50个高频答辩问题-技术篇](https://berserker287.github.io/2023/06/13/50%E4%B8%AA%E9%AB%98%E9%A2%91%E7%AD%94%E8%BE%A9%E9%97%AE%E9%A2%98-%E6%8A%80%E6%9C%AF%E7%AF%87/)

[计算机毕设答辩时都会问到哪些问题？](https://www.zhihu.com/question/31020988)

[计算机专业毕业答辩小tips](https://zhuanlan.zhihu.com/p/145911029)

#### 接JAVAWEB毕设，纯原创，价格公道，诚信第一

`网站建设、小程序、H5、APP、各种系统 选题+开题报告+任务书+程序定制+安装调试+项目讲解+论文+答辩PPT`

More info: [悲伤的橘子树](https://berserker287.github.io/)

<p><img align="center" src="https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/%E5%90%88%E4%BD%9C%E7%89%A9%E6%96%99%E6%A0%B7%E5%BC%8F%20(3).png" alt="fankekeke" /></p>
