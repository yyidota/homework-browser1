# 100个dom节点，重排重绘测试
### 100个dom节点初始化
![节点初始化](./init.png)
### 重排结果点击动态图
![重排结果点击动态图](./result.gif)
### 重排集中处理
![重排集中处理](./chongpaijizhong.png)
### 重排集中处理
![重排分开处理](./chongpaifenli.png)

### 结论
+ 通过测试盒子计算类的和滚动在重排中引起的性能消耗较大
+ 引起重排的因素
  + 盒子计算
  + 滚动相关
  + 获得焦点
  + 鼠标事件