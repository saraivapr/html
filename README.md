<!DOCTYPE html>
<htl lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon" href="relogio.png" type="image/x-icon">
    <title>Relógio Digital</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div>
        <h1>Horário de Brasilia</h1>
        <p>Acerte seu relógio com a hora certa!</p>
    </div>
    <div id="container">
        <h2>Horas :</h2>
        <div id="relogio">00:00:00</div>
    </div>
 

    <footer>
        
        <a href="https://github.com/saraivapr/html/settings" target="_blank"><p>&copy;<i>rafael</i></p></a>
    </footer>
</body>
</html>


unction hora(){
    //relogio recebe data atual
    let relogio = document.getElementById('relogio')

    let tempo = new Date();
    let horas = tempo.getHours();
    let minutos = tempo.getMinutes();
    let segundos = tempo.getSeconds();

    relogio.innerHTML =`${horas}:${minutos}:${segundos}`
   




  }
  
  hora();




       body {
    font-family: Arial, sans-serif;
    background-color: #222;
    color: white;
    text-align: center;
    font-size: 2rem;
}
#container{
    background-color: rgba(255, 255, 255, 0.3);
}


#relogio {
    font-size: 3rem;
    font-weight: bold;
    margin-top: 10px;
}
    







