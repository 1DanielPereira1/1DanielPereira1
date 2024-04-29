<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ligar/Desligar Monitor</title>
<style>
  body {
    background-color: #F5F5F5;
    text-align: center;
  }

  h2 {
    color: #00CED1;
  }

  p {
    color: #4169E1;
  }

  button {
    background-color: #CD853F;
    color: #fff;
    padding: 10px 20px;
    margin: 10px;
    cursor: pointer;
  }

  button:hover {
    background-color: #D2691E;
  }

  img {
    margin-top: 20px;
  }
</style>
</head>
<body>

<h2>Ligar e Desligar o Monitor</h2>
<p>Com JavaScript podes fazer isto e MUITO MAIS!!!</p>
<p>Este programa consiste em usar JavaScript para Criar Botões que Ligam e Desligam o Monitor<br><br>Clica no Botão para Ligar o Monitor</p>

<button onclick="document.getElementById('myImage').src='https://img.pccomponentes.com/articles/15/154787/1402-philips-243v7qdab-24-ips-led-fullhd-comprar.jpg'">Ligar o Monitor </button>
<img id="myImage" src="https://med.greatecno.com/358404-large_default/monitor-lcd-full-hd-philips-v-line-273v7qdsb-00.jpg" style="width:300px">
<button onclick="document.getElementById('myImage').src='https://med.greatecno.com/358404-large_default/monitor-lcd-full-hd-philips-v-line-273v7qdsb-00.jpg'">Desligar o Monitor</button>

</body>
</html>
