<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>菜鸟教程(runoob.com)</title>
<script>
function displayDate(){
	document.getElementById("demo").innerHTML=Date();
}
</script>
</head>
<body>

<h1>我的第一个 JavaScript 程序</h1>
<p id="demo">这是一个段落</p>

<button type="button" onclick="displayDate()">显示日期</button>

</body>
</html>
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>菜鸟教程(runoob.com)</title>
</head>
<body>

<p>整数最多为 15 位。</p>

<button onclick="myFunction()">点我</button>

<p id="demo"></p>

<script>
function myFunction() {
    var x = 999999999999999;
    var y = 9999999999999999;
    document.getElementById("demo").innerHTML = x + "<br>" + y;
}
</script>