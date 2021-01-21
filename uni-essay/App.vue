<script>
	export default {
		//应用初始化完成触发，全局只触发一次
		onLaunch: function() {
			console.log('App Launch')
			//用户登录。初始化等操作
		},
		//应用启动或从后台进入前台显示时触发
		onShow: function() {
			console.log('App Show')
		},
		//应用从前台进入后台时触发
		onHide: function() {
			console.log('App Hide')
		},
		
		//不常用
		//应用报错时触发
		onError:function(){	
		},
		//对nuve页面发送的数据进行监听
		onUniNViewMessage:function(){	
		},
		//对未处理的Promise拒绝实际监听函数
		onUnhandledRejection:function(){			
		},
		//页面不存在监听函数
		onPageNotFound:function(){			
		},
		//监听系统主题变化
		onThemeChange:function(){		
		}
	}
</script>

<style>
	/*每个页面公共css */
</style>
