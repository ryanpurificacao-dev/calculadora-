<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <link rel="stylesheet" href="estilo.css">
    <title>Calculadora</title>
    <script src="https://code.jquery.com/jquery-2.2.4.min.js" integrity="sha256-BbhdlvQf/xTY9gja0Dq3HiwQF8LaCRTXxZKRutelT44=" crossorigin="anonymous"></script>

</head>
<body>
    <div class="central">
        <p class= "title"> Área do retângulo</p>
        <fieldset>
        
        <img src="download.png" alt="">
        <form>
        <p>
            <label for="idBaseRetangulo">Base</label>
            <input type ="number" name= "baseRetangulo" id="idBaseRetangulo">
        </p>
        <p> Área do retângulo</p>
        <p>
           <label for="alturaRetangulo">altura</label>
           <input type ="number" name= "alturaRetangulo" id="alturaRetangulo">
        </p>
        <input type="button" value="Calcular"
             onclick="areaRetangulo(baseRetangulo.value,alturaRetangulo.value)"
            
             >

        </form>
        <p id="ResultadoRetangulo"></p>
    </fieldset>

    <p class="title">Área do quadrado</p>
    <fieldset>
        
    <img src="download (1).png"alt=""> 
    <form>
        <p>
        </p>
        <p> Área do quadrado</p>
        <p>
           <label for="ladoQuadrado">lado</label>
           <input type ="number" name= "ladoQuadrado" id="ladoQuadrado">
        </p>
        <input type="button" value="Calcular"
             onclick="areaQuadrado(ladoQuadrado.value)">

    </form>
      <p id="ResultadoQuadrado"></p>
</fieldset> 

<p class= "title"> Área do trapézio</p>
<fieldset>
        
    <img src="unnamed.jpg"alt=""> 
    <form>
        <p>
            <label for="idBase">Base</label>
            <input type ="number" name="baseMaior" id="idBaseRetangulo">
        </p>
        <p> Área do Trapezio</p>
        <p>
            <label for="idbase">base</label>
            <input type ="number" name="baseMenor" id="idbaseRetangulo">
           <label for="Altura">Altura</label>
           <input type ="number" name= "altura" id="h">
        </p>
        <input type="button" value="Calcular"
             onclick="areaTrapezio(baseMaior.value,baseMenor.value, altura.value)">

    </form>
      <p id="ResultadoTrapezio"></p>
</fieldset>
</div>

<script src="app.js"></script>
</body>
</html>
    
</body>
</html>
