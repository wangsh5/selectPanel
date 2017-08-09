# selectPanel
基于jQuery仿淘宝移动端收货地址类似的同一页面逐级渲染要选数据的插件
## 效果图
![selectPanelImg](images/1.png =100x100) ![selectPanelImg](images/2.png =100x100) ![selectPanelImg](images/3.png =100x100)
## 使用方法
### 引用selectPanel.js
```javascript
  $(ele).showPanel({
		data:data,//需渲染的数据，
		codeName:code,//存储code返回值
	})
```
### 暂时只支持单选并且选到最末级
