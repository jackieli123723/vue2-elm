
## 前言

vue2的发布后自己也研究了一段时间，奈何公司的技术栈是以react为主，没有机会好好利用vue2去做一个完整的项目。虽然写了几个demo，但和写一个完整的项目还是有很大差别的。于是自己想着用空余的时间写一个项目，思来想去选择了饿了么web端，因为经常用它来点外卖，对布局比较熟悉。

首先遇到的问题当然是跨域，我们启动本地服务器是获取不到官网数据的，这是跨域的。当然解决的方法很多，nginx反向代理，webpack-dev-server的proxy。这里我用的是 http-proxy-middleware 其实它们的原理是一样的。

__此项目纯属个人瞎搞，正常下单请选择饿了么官方客户端。__


## 技术栈
vue2 + vue-rotuer + vuex + webpack + ES6 + fetch + less + http-proxy-middleware反向代理 

## 目标功能

- [ ] 定位功能
- [ ] 选择城市
- [ ] 根据输入地址，搜索附近餐馆
- [ ] 附近商家列表展示
- [ ] 根据距离、销量、评分、特色菜等进行排序和筛选
- [ ] 单个餐馆的详细信息展示，商品列表，优惠活动
- [ ] 餐馆及单个商品的评价列表展示、筛选
- [ ] 购物车功能
- [ ] 登陆
- [ ] 注册
- [ ] 个人中心
- [ ] 帐户信息
- [ ] 服务中心
- [ ] 订单列表
- [ ] 正常下单
- [ ] 付款(写着玩，不当真)

说明：因为并不是elm官方，所以预计最多只能做到下单这一步，下单成功后可以在手机客户端查看并付款。
     最关键的点在于登陆功能的实现。


## 项目运行
```
git clone https://github.com/vue-elm/vue2-elm.git

cd vue2-elm

npm install
```

### 编译环境
```
npm run dev
```


### 线上版本
```
npm run build
```

