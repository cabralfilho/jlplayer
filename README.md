<! DOCTYPE html>
<html lang = "pt-br">

<head>
    <meta charset = "UTF-8">
    <meta name = "viewport" content = "width = device-width, initial-scale = 1.0">
    <meta http-equiv = "Compatível com X-UA" content = "ie = edge">
    <title> JLPlayer - Reprodutor de vídeos </title>

    <! - Estilo de link jlplayer.css ->
    <link rel = "stylesheet" href = "https://raw.githubusercontent.com/cabralfilho/jlplayer/master/jlplayer.css">

    <style>
        *, * :: antes, * :: depois {margem: 0; preenchimento: 0;}
        .video-container {largura: 500px;}
    </style>

</head>

<body>

    <div class = "video-container">

        <! - Chamar elemento vídeo com classe jlplayer-video ->
        <video preload = "none" class = "jlplayer-video">
            <source src = "ajax-intro.mp4" type = "video / mp4">
            <! - <track kind = "captions" src = "legenda.vtt" default> ->
        </video>

    </div>

    <! - Inclusão jlplayer ->
    <script src = "https://raw.githubusercontent.com/cabralfilho/jlplayer/master/jlplayer.js" async> </script>

</body>

</html>
