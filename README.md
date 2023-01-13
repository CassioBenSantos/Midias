# Midias
Imagens que se adequam ao tamanho de tela e mídia de áudio 
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mídias em Html5</title>
</head>
<body>
    <h1>Imagens Dinámicas</h1>
    <p>Tente abrir imagens em dispositivos diferentes com tamanhos diversos no site ou simplesmente aumente e diminua o tamanho no seu navegador</p>

    <picture>
        <source media="(max-width: 750px)" srcset="imagens/foto-p.png" type="image/png">
        <source media="(max-width: 950px)" srcset="imagens/foto-m.png" type="image/png">
    
    <img src="imagens/foto-g.png" alt="imagem flexivel">
</picture>

<h1>Reproduzindo Áudio</h1>
<P>Vamos aprender a reproduzir áudio em Html5</P>


<audio preload="metadata" autoplay controls loop>
<source src="midias/maid-with-the-flaxen-hair.mp3.mp3" type="audio/mpeg">
<source src="midias/maid-with-the-flaxen-hair.ogg" type="audio/ogg">
<source src="midias/maid-with-the-flaxen-hair.wav" type="audio/wav">
<p>Infelizmente seu navegador não consegue reproduzir áudio. <a href="midias/maid-with-the-flaxen-hair.mp3"> Clique aqui para baixar arquivo em mp3 </a></p>
</audio>


</body>
</html>
