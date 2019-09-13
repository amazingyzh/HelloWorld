<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<title></title>
		<script src="vue.js" type="text/javascript" charset="utf-8"></script>
	</head>
	<body>
		<div id="app">
			{{massage}}
		</div>
		<script type="text/javascript">
			//let(变量)/const(常量)
			const app1
			 = new Vue({
				//把app元素传给vue实例
				el:"#app",//用于挂载要管理的元素
				data:{//定义数据
					massage:"Hello World"
				}
			})
		</script>
	</body>
</html>
