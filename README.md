# Design of a Standard Calculator

## AIM:

To design a web application for a standard calculator.

## DESIGN STEPS:

Step 1:

Clone the github repository and create Django admin

interface.

Step 2:

Change settings.py file to allow request from all hosts.

'Step 3:

Use CSS for creating attractive colours

Step 4:

Write javascript program for implementing five different

operations

'Step 5:

Validate the HTML and CSS code.

Step 6:

Publish the website in the given URL

PROGRAM:

calc.html

<1DOCTYPE html> <html lang="en">

<<head>

cneta charset="UTF-8"> cneta name="viewport" content="width=device-

width, initial-scale-1.8">

cneta http-equiv="X-UA-Compatible"

content-i-edge">

<link rel="stylesheet" href="/static/css/style.css">

<title>Calculator</title>

</head>

<body>

<div class="container">

<h1>Calculator</u>>

<div class="calculator"> <input types"text" name="screen"

id="screen">

<table>

<tr>

<td><button>(</button></td>

<td><button>)</button></td>x <td><button>C</button></td>

<td><button>X</button></td>

</tr>

strs

<td><button>7</button></td>

<td><button>8</button></td>

<td><button>@</button></td>

ctd><button>X</button></td>

</tr>

<td><button>4</button></td> <td><button>5</button></td> <td><button>6</button></td>

</tm

<tr> <td><button>1</button> </td> <td><button>2</button></td> <td><button>1</button> </td> <td><button>+</button> </td

<tr>

<td><button>8</button></td>

<td><button>.</button></td> <td><button>/</button></td> <td><button>=</button></td>

</tr> </table>

</div>

</div>

</body>

<script src="/static/35/index.js"></script>

</html>

style.css

.container


text-align: center; margin-top:23px

table margin: auto;

Input

border-radius: 21px;

border: 5px solid #244624;

font-size:34px;

height: 65px;

width: 450px;

2

button

border-radius: 20px;

font-size: 40px;

background: #978fa0;

width: 182px;

height:

90px;

margin: 6px;

.calculator

border: 4px solid #13695d; background-color: #ff99f7;

padding: 23px;

border-radius: 53px;

display: inline-block;

font-size: 20px;

Font-family: Courier New, Courier,

monospace;

let screen document.getElementById("screen");

buttons document.querySelectorAll('button)

let screenValue="

for (item of buttons) ( item,addEventListener("click", (e) => {

buttonText = e.target.innerText; console.log("Button text is

buttonText);

IF (buttonText == 'x') { buttonTextes

screenvalue buttonText;

screen.value = screenValue;

else if (buttonText == "c')[ screenvalue "

screen, value screenValue:

else if (buttonText) screen value eval(screenValue);

else {

screenValue + buttonText; screen.value = screenvalue

}

## OUTPUT:
![calci draw](https://github.com/manikandan26052004/standard-calculator/assets/121999845/d7264f7a-fd59-4edc-b603-7e7328f17945)



## Result:
Tthe program for designing a simple calculator using javascript executed successfully.

