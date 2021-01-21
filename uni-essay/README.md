# uni-learn
uni学习记录
## 应用生命周期
详见App.vue ，且只能在App.vue中进行监听，其他页面监听无效
## 页面生命周期
详见index.vue，罗列了通用的生命周期
## 项目结构
* components - 自定义组件的目录
* pages - 页面的存放目录
* static - 静态资源的目录
* unpackage - 编译后的文件存放目录
* utils - 公用的文件
* App.vue - 应用生命周期和全局css
* main.js - 应用入口 引用全局文件，三方库等
* manifest.json - 项目配置
* pages.json  - 页面配置   所有页面都要在这里注册，tabbar也在这里设置 
* uni.scss  全局变量

## tabBar
```
"tabBar":{
		"color": "#BBBBBB",
		"selectedColor": "#4399fc",
		"borderStyle": "black",
		"backgroundColor": "#ffffff",
		"list":[{
				"pagePath": "pages/home/home",
				//40kb,81*81
				"iconPath": "static/menubar/tab_home_unselect.png",
				"selectedIconPath": "static/menubar/tab_home_select.png",
				"text": "首页"
			}
			]
	}
 在具体页面中，可以使用onTabItemTap()进行监听tabBar点击（做页面重新渲染），也可在onShow()立监听
```