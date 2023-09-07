
<html>
<body>
Enter First Number:<input type="text" id="num1">
<br><br>
Enter Second Number:<input type="text" id="num2">
<br><br>
Result=<input type="text" id="result">
<br><br>
<button onclick="sum()">Addition</button>
<button onclick="sub()">Sunstraction</button>

<script>
function sum()
{
var n1=parseInt(document.getElementById("num1").value);
var n2=parseInt(document.getElementById("num2").value);
n=n1+n2;
document.getElementById("result").value=n;
}

function sub()
{
var n1=parseInt(document.getElementById("num1").value);
var n2=parseInt(document.getElementById("num2").value);
n=n1-n2;
document.getElementById("result").value=n;
}

</script>
</body>
</html>

