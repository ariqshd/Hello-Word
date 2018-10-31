<!DOCTYPE html>
<html>
<head>
	<!-- <link rel="stylesheet" type="text/css" href="style.css">
	<script type="text/javascript" src="sketch.js"></script>
	 -->
	<!--
	<style type="text/css">
		p{
			font-family: "Harrington";
			font-size: 50%
		}
		table,td{
			border:1px solid;
			background-color: cyan;
		}

	</style>
-->
	<title>menariq.com</title>
</head>
<body>
	<p><canvas id="canvas1" width="720" height="480"></canvas></p>
	<input type="number" id="input1" placeholder="Panjang Kotak">
	<input type="number" id="input2" placeholder="Lebar Kotak">
	<button onclick="process()" id="button1">Click Me</button>
	<div id="output"></div>
	<script type="text/javascript">
		function process(){

			var a = document.getElementById("input1").value;
			var b = document.getElementById("input2").value;
			var c=document.getElementById("canvas1");
			var ctx=c.getContext("2d");
			ctx.rect(20,20,a,b);
			ctx.fillStyle="#696969";
			ctx.stroke();


		}
		
	</script>

</body>
</html>
