<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Calculadora </title>
    <style>
        *{
            margin: 0;
            padding: 0;
        }
        .fundo{
            background-image: linear-gradient(45deg, black, purple);
            height: 100vh;
            color: white;
            font-family: Arial, Helvetica, sans-serif;
        }
        .calculadora{
            position: absolute;
            background-color: black;
            top: 50%;
            left: 50%;
            transform: translate(-50%, 50%);
            border-radius: 15px;
            padding: 15px;
        }
    
    </style>
</head>
<body>
    <div class="fundo">
   <div class="calculadora">
   <h1>Calculadora</h1>
   <p id="resultado"></p>
   <table>
      <tr> 
        <td><button>C</button></td>
        <td><button><</button></td>
        <td><button>/</button></td>
        <td><button>X</button></td>
      </tr>
      <tr> 
        <td><button>7</button></td>
        <td><button>8</button></td>
        <td><button>9</button></td>
        <td><button>-</button></td>
      </tr>
      <tr> 
        <td><button>4</button></td>
        <td><button>5</button></td>
        <td><button>6</button></td>
        <td><button>+</button></td>
      </tr>
      <td><button>1</button></td>
        <td><button>2</button></td>
        <td><button>3</button></td>
        <td rowspan="2"><button>=</button></td>
      </tr>
    </tr>
    <td colspan="2"><button>0</button></td>
      <td><button>.</button></td>
    </tr>
   </table>
</div>

  
</body>
</html>
