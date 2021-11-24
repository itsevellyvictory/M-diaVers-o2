<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KD MINHA MÉDIA</title>
   
    <style>
        p.solid {border-style: solid;}
   body{
       background-color:rgb(145, 10, 10);
       
   }

   h1{
    text-align: center;
       color:rgb(255, 251, 6);
       font: normal 30pt; 
       border-width: thin;
       border-style: solid;
       border-color: white ;  
   }

  p{
    text-align: center;
    color:white;
    font: normal 20pt Arial;
    border-color:yellow ;
  }
  p{
    text-align: center;
    color:white;
    font: normal 20pt Arial;
    border-color:yellow ;
  }
  p{
    text-align: center;
    color:white;
    font: normal 20pt Arial;
    border-color:yellow ;
  }
  p{
    text-align: center;
    color:white;
    font: normal 20pt Arial;
    border-color:yellow ;
  }
    </style>
</head>
<body>
    <h1> KD MINHA MÉDIA?!</h1>
    <p> 
        Digite a primeira nota  <input id="nota1" type="number"><br /></p>
     <p>
        Digite a segunda nota   <input id="nota2" type="number"><br /><p>
     <p>Digite a terceira nota  <input id="nota3" type="number"> <br /><p>
     <p>Digite a quarta nota    <input id="nota4" type="number"> <br  /><p>
        <button onclick="media()">Calcular Média</button>
 
    <script type="text/javascript">

        function media(){
         var nota1 = parseFloat(document.getElementById("nota1").value);
         var nota2 = parseFloat(document.getElementById("nota2").value);
         var nota3 = parseFloat(document.getElementById("nota3").value);
         var nota4 = parseFloat(document.getElementById("nota4").value);
    
         var media = (nota1 + nota2 + nota3 + nota4) /4 ;
    
         document.write(`a MÉDIA É ${media}`);
        }
     </script>
     
</body>
 


</html>
