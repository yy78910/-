<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
	<style type="text/css">
		.rrr{
			width: 140px;
			height: 30px;
			line-height: 30px;
			background: pink;
			color: yellow;
			font-style: 14px;
			text-align: center;
			border: 5px;
			cursor: pointer;
			margin: 0 auto;
		}
	</style>
</head>
<body>
	<input type="button" name="aaa" value="点击" onclick="ppp()"/>
	<div class="rrr" onmouseover="eee(this,'#f00')" onmouseout="zzz(this,'#ff0')">欢迎贾老师</div>
	<div class="rrr" onmouseover="eee(this,'#0d0')" onmouseout="zzz(this,'#333')">欢迎贾老师</div>
	<script type="text/javascript">
		function ppp() {
			alert('欢迎贾超贤老师');
		}
		function eee(rrr,bgColor) {
			rrr.style.background=bgColor;
		}
		function zzz(rrr,bgColor) {
			rrr.style.background=bgColor;
		}
		alert('欢迎贾老师');
	</script>
</body>
</html>
