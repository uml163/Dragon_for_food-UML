---
layout: default
title: 产品特征库
---

## 初级产品特征库
{:.no_toc}

* 目录
{:toc}

| 版本  |   日期    | 描述 |  作者   |
| --:  | :-------: | --: | -----   |
| v1.1 | 2019-3-15 | 仅根据第一版用例模型构建 |  zfr0411 |

### 产品特性

| ID	|Name	|Imp	|Est	|How to demo	|Notes|
|-|:--:|:--:|----|----|------|
|1	|顾客登录	|10	|8	|顾客通过手机短信验证码的方式实现注册及登录	|控制发验证码的时间间隔|
|2	|顾客取号排队	|15	|10	|顾客领取排队号码开始等待并且可以查询排队情况	|实时更新排队情况|
|3	|顾客扫码点餐	|30	|14	|顾客扫描餐桌上的二维码，进入菜单页面，浏览菜单，加入购物车，进行下单	|确保订单计算正确|
|4	|顾客查询订单	|30	|15	|顾客能够查询到当前订单及历史订单，然后可以取消当前订单，或者进行结账	结账需要调用微信支付接口|
|5	|顾客点评	|20	|10	|顾客能够对订单发表自己的点评并查看历史评价	|点评订单要求订单的状态为已完成|
|6	|后厨查询订单	|10	|5	|后厨在顾客下单后查询订单并制作相应的菜品	|后厨只有查询权限没有修改权限|
|7	|服务员查询订单	|10	|5	|服务员查询订单信息后将菜品送至相应的餐桌	|服务员只有查询权限没有修改权限|
|8	|主管查询订单	|20	|10	|主管查询订单并对订单进行审核	|主管有权取消订单
|9	|主管查询评价	|20	|3	|主管查看顾客给出的评价，做出改进	|主管能对评价进行回复但不能删除|
|10	|主管统计收入	|10	|5	|主管统计一天的营业额	|营业额的计算要删除已取消的订单|
|11	|主管管理用户	|10	|4	|对用户进行身份审核	|
|12	|主管管理菜品	|20	|5	|主管对菜品和规格进行增删改查	|
|13	|主管管理餐位	|30	|5	|生成对应桌数的唯一二维码	|