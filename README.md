### Created by <a href="https://github.com/micku7zu">micku7zu </a>
### updated by <a href="https://github.com/wmbolles">wmbolles </a>

# FlexiCalc
<img src="https://github.com/wmBolles/Calculator/blob/master/images/Calc.png">

# A Flexible Hover Calculator

<img src="https://github.com/wmBolles/Calculator/blob/master/images/Calcm.png">

### TryIt
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://github.com/wmBolles/FlexiCalc/blob/master/source/style.css">
    
    <title>wmcalc</title>
</head>
<body>
    <div class="container">
        <form class="calculator" name="calc">
           <input type="text" readonly class="value" name="txt"/>
           <span class="num clear" onclick="calc.txt.value = ''">c</span>
           <span class="num" onclick="document.calc.txt.value +='/'">/</span>
           <span class="num" onclick="document.calc.txt.value +='*'">*</span>
           <span class="num" onclick="document.calc.txt.value +='7'">7</span>
           <span class="num" onclick="document.calc.txt.value +='8'">8</span>
           <span class="num" onclick="document.calc.txt.value +='9'">9</span>
           <span class="num" onclick="document.calc.txt.value +='-'">-</span>
           <span class="num" onclick="document.calc.txt.value +='4'">4</span>
           <span class="num" onclick="document.calc.txt.value +='5'">5</span>
           <span class="num" onclick="document.calc.txt.value +='6'">6</span>
           <span class="num" onclick="document.calc.txt.value +='+'">+</span>
           <span class="num plus" onclick="document.calc.txt.value +='1'">1</span>
           <span class="num" onclick="document.calc.txt.value +='2'">2</span>
           <span class="num" onclick="document.calc.txt.value +='3'">3</span>
           <span class="num" onclick="document.calc.txt.value +='0'">0</span>
           <span class="num" onclick="document.calc.txt.value +='00'">00</span>
           <span class="num" onclick="document.calc.txt.value +='.'">.</span>
           <span class="num equal" onclick="document.calc.txt.value =eval(calc.txt.value)">=</span>
        </form>        
    </div>
   
        <script type="text/javascript" src="https://github.com/wmBolles/FlexiCalc/blob/master/source/vanilla-tilt.js"></script>
<script type="text/javascript">
	VanillaTilt.init(document.querySelector(".container"), {
		max: 55,
		speed: 4000
	});
    </script>
</body>
</html>
