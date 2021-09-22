<!DOCTYPE html>
<html>
<head>
	<title>Calculator</title>
</head>
<body>
	<style >
		button:hover,.b1:hover{
			background-color: rgb (74,248,83);
		}
		button:active,b1:active{
			background-color: #6bc953;
		}
		input{
			height: 46px;
			width: 250px;
			outline: none;
			text-align:center;
			font-size:23px;
			color: blue;
			border: 5px solid #690f51;
			border-radius: 9px;
		}
		.number{
			height: 60px;
			width: 60px;
			outline: none;
			font-size:20px;
			border: 3px solid #690f51;
			border-radius: 30px;
			background-color: #33fff1;

		}
		.control{
			height: 60px;
			width: 60px;
			outline: none;
			font-size:20px;
			border: 3px solid #690f51;
			border-radius: 30px;
			background-color: #fc913a;
		}
		.b1{
			width: 250px;
			height: 60px;
			outline: none;
			font-size:20px;
			border: 3px solid #690f51;
			border-radius: 11px;
			background-color: #ff4e50;
		}
		div{
			width: 260px;
			border-radius: 10px;
			background-color: #690f51;
		}
	</style>
<center>
	<div>
		<input id="i1" disabled>
		<button class="number" onclick ="window.i1.value +='1'">1</button>
		<button class="number" onclick ="window.i1.value +='2'">2</button>
		<button class="number" onclick ="window.i1.value +='3'">3</button>
		<button class="control" onclick ="window.i1.value +='/'">/</button><br>
		<button class="number" onclick ="window.i1.value +='4'">4</button>
		<button class="number" onclick ="window.i1.value +='5'">5</button>
		<button class="number" onclick ="window.i1.value +='6'">6</button>
		<button class="control" onclick ="window.i1.value +='*'">*</button><br>
		<button class="number" onclick ="window.i1.value +='7'">7</button>
		<button class="number" onclick ="window.i1.value +='8'">8</button>
		<button class="number" onclick ="window.i1.value +='9'">9</button>
		<button class="control" onclick ="window.i1.value +='-'">-</button><br>
		<button class="number" onclick ="window.i1.value +='0'">0</button>
		<button class="number" onclick ="window.i1.value +='.'">.</button>
		<button class="control" onclick ="window.i1.value = eval(window.i1.value)">=</button>
		<button class="control" onclick ="window.i1.value +='+'">+</button><br>
		<button class="b1" onclick ="window.i1.value = window.i1.value=' '">Clear</button>
	</div>
</center>

</body>
</html>
