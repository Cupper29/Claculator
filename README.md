# Claculator
My first HW from my Uncle :)

My first steps in Github,22/1/2021 today desperately my uncle asked for my calculator jsjsjs.


<!Doctype html>
<html>
<head>

<title>
Calculator 
</title>
<link rel= "stylesheet" type="text/css" href="style.css">
</head>
<body>
<form class="calculator" name="calc">
  <input class= "value" type="text" name="txt" readonly="">
  <span class="num clear" onclick="document.calc.txt.value =''" >c</span>
  <span class="num" onclick="document.calc.txt.value +='/'" >/</span>
  <span class="num" onclick="document.calc.txt.value +='*'" >*</span>
  <span class="num" onclick="document.calc.txt.value +='7'" >7</span>
  <span class="num" onclick="document.calc.txt.value +='8'" >8</span>
  <span class="num" onclick="document.calc.txt.value +='9'" >9</span>
  <span class="num" onclick="document.calc.txt.value +='-'" >-</span>
  <span class="num" onclick="document.calc.txt.value +='4'" >4</span>
  <span class="num" onclick="document.calc.txt.value +='5'" >5</span>
  <span class="num" onclick="document.calc.txt.value +='6'" >6</span>
  <span class="num plus" onclick="document.calc.txt.value +='+'" >+</span>
  <span class="num" onclick="document.calc.txt.value +='3'" >3</span>
  <span class="num" onclick="document.calc.txt.value +='2'" >2</span>
  <span class="num" onclick="document.calc.txt.value +='1'" >1</span>
  <span class="num" onclick="document.calc.txt.value +='0'" >0</span>
  <span class="num" onclick="document.calc.txt.value +='0'" >00</span>
  <span class="num" onclick="document.calc.txt.value +='.'" >.</span>
  <span class="num equal" onclick="document.calc.txt.value = eval(calc.txt.value)" >=</span>
</form>
</body>
</html>




*
{
       margin:0;
       padding:0;
       box-sizing:border-box;
       font-family:'Poppins', sans-serif;
 }
body
{
     display:flex;
     justify-content:center;
     align-items:center;
     min-height:100vh;
     background: #091921;
}
.calculator
{
 position:relative;
 display:grid;
}
.calculator .value
{
 grid-column:span 4;
 height:100px;
 text-align:right;
 border:none;
 padding:10px;
 font-size:18px;
}
.calculator span
{
 display:grid;
 width:60px;
 height:60px;
 color:#fff;
 background:#0c2835;
 place-items:center;
 border:1px  solid rgba(0,0,0,1);
}
.calculator span:active
{
 background:#74ff3b;
 color:#111;
}
.calculator span.clear
{
 grid-column:span 2;
 width:120px;
 background:#ff3077;
}
.calculator span.plus
{
 grid-row:span 2;
 height:120px;
}
.calculator span.equal
{
 background:#03blff;
}

