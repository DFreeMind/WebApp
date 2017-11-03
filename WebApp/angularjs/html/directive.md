# 指令

## 属性简介

### 使用方法如下：
```javascript
	app.directive("myAlert",function(){
			return { 
				/**
				 * 表示此指令可以用在什么地方，可以选的有E(Element)、A(Attribute)、
				 * C(Class)、M(Comment)，M并不常用。默认为 EA
				 */
				restrict:"EA",
				
				/**
				 * 表示是否替换指令元素
				 */
				replace:true,
				template:"<div>ε＝ε＝ε＝(#>д<)ﾉ 我被替换了</dive>"
			};
		})
```

#### 参数详解

##### `replace`

replace 可以选的有两个值 `true` 和 `false` ， 当为`true`时页面上的自定义指令会被替换 ，当为`false`
时页面上的指令不会被替换，而是将template或者templateUrl中的内容追见到自定义指令中。
 
 * 	当为`true` 时






















