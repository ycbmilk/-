## attr & prop
###什么是attribute
	html标签的预定义 自定义属性

###什么是property
	js对象的原生属性

### 每一个预定义的attribute 都会有一个property与之对应

###什么是布尔值属性 什么是非布尔值属性
	property的属性值为布尔值类型布尔值属性;反之 是非布尔值属性


###浏览器认谁  用户操作的是谁
	property

###property 和 attribute之间的关系
	非布尔值
		实时同步
	布尔值
		property永远不会同步attribute
		如果没有动过property
			attribute会实时同步property
		如果动了property
			attribute不会同步property

