# html-javascript-calculator
Beginner html/Javascript code project


<html>
<head>
<title>iCalculator</title>
</head>

<body> bgcolor="B8860B"                     // background color//
<center><br> //center calculator//
<h1><b><font color ="white" style = font-size:70">Javascript Calculator</font></h1></B>     //calculator heading, bold//
<hr size=20 color="black"> //horizontal line//
<div style = "width:261px; background:"FFF8DC">
<form name ="Calculator">
<input name ="display" placeholder ="0" style="width:254px; height:60px; text-align:right; font-size:30; border-radius:8px; margin"/>
<br>
<input type ="button" value="7" onClick ="document.Calculator.display.value ="7" style ="width:60px; height:60px; font-size:30; border-radius:8px; margin:3px"/>
<input type ="button" value="8" onClick ="document.Calculator.display.value ="8" style ="width:60px; height:60px; font-size:30; border-radius:8px"/>
<input type ="button" value="9" onClick ="document.Calculator.display.value ="9" style ="width:60px; height:60px; font-size:30; border-radius:8px"/>
<input type ="button" value="+" onClick ="btnplus()" style ="width:60px; height:60px; font-size:30px; border-radius:8px"/>
<br>
<input type ="button" value="4" onClick ="document.Calculator.display.value ="4" style ="width:60px; height:60px; font-size:30; border-radius:8px; margin:3px"/>
<input type ="button" value="5" onClick ="document.Calculator.display.value ="5" style ="width:60px; height:60px; font-size:30; border-radius:8px"/>
<input type ="button" value="6" onClick ="document.Calculator.display.value ="6" style ="width:60px; height:60px; font-size:30; border-radius:8px"/>
<input type ="button" value="-" onClick ="btnplus()" style ="width:60px; height:60px; font-size:30px; border-radius:8px"/>
<br>
<input type ="button" value="1" onClick ="document.Calculator.display.value ="1" style ="width:60px; height:60px; font-size:30; border-radius:8px; margin:3px"/>
<input type ="button" value="2" onClick ="document.Calculator.display.value ="2" style ="width:60px; height:60px; font-size:30; border-radius:8px"/>
<input type ="button" value="3" onClick ="document.Calculator.display.value ="3" style ="width:60px; height:60px; font-size:30; border-radius:8px"/>
<input type ="button" value="*" onClick ="btnmult()" style ="width:60px; height:60px; font-size:30px; border-radius:8px"/>
<br>
<input type ="button" value="0" onClick ="document.Calculator.display.value ="0" style ="width:60px; height:60px; font-size:30; border-radius:8px; margin:3px"/>
<input type ="button" value="%" onClick =btnmod()" style ="width:60px; height:60px; font-size:30; border-radius:8px"/>
<input type ="button" value="." onClick =btndot()" style ="width:60px; height:60px; font-size:30; border-radius:8px"/>
<input type ="button" value="/" onClick =btndiv()" style ="width:60px; height:60px; font-size:30; border-radius:8px"/>
<br>
<input type ="button" value="=" onClick ="document.Calculator.display.value = eval(document.Calculator.display.value)"
style ="width:124px; height:60px; font-size:30px; border-radius:8px; margin:3px"/>
<input type ="button" value="C" onClick ="btnclear()" style ="width:124px; height:60px; font-size:30px; border-radius:8px "/>

</form></div>
<hr size=20 color = "black">
<SCRIPT>
function btnplus()
{   document.Calculator.display.value +="+";
document.Calculator.display.style.textAlign="right";}
function btnsub()
{   document.Calculator.display.value +="-";
document.Calcultor.display.style.textAlign="right";}
function btnmult()
{   document.Calculator.display.value +="*";
document.Calculator.display.style.textAlign="right";}

</SCRIPT>
</center
</BODY>
</HTML>
