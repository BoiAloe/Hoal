# Hoal
<html>
<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>Nobia</title>
    <meta name='viewport' content='width=device-width, initial-scale=1'>
    <style>
        body {
            background-color: pink;
        }
    </style>
    <script>
        function accionParaCuandoEllaDigaQueSi(){
            alert('ahora ya somos nobios <3');
        }

        function mueveElBoton(){
            width = window.innerWidth;
            height = window.innerHeight;

            newWidth = (Math.random() * width);
            newHeight = (Math.random() * height);

            document.getElementById('btnNo').style.position = "absolute";
            document.getElementById('btnNo').style.left = newWidth + "px";
            document.getElementById('btnNo').style.top = newHeight + "px";
            

        }
    </script>
</head>
<body>
    <h3>Hoal fany, quieres ser mi nobia?</h3>
    <input type="button" onclick="accionParaCuandoEllaDigaQueSi()" id="btnSi" value="Si" />
    <input type="button" id="btnNo" onmouseover="mueveElBoton()" value="No" />
    <img src=![20201030_111444](https://user-images.githubusercontent.com/84035355/117862085-dd527680-b257-11eb-9199-79366f690fc0.jpg)
 width="200">
</body>
</html>
