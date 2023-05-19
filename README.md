<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Scrollarrow</title>
    <style>
        div{
            background-color: aqua;
            width: 400px;
            height: 100px; 
            margin: auto;
        }
    </style>
</head>
<body>
    <div id="width">

    </div>
    <br>
    <br>
    <div id="height">

    </div>
    <button id="btn" class="hidden">Up</button>

    <script>
        var w=document.getElementById("width");
        var h=document.getElementById("height");
        window.onresize=function(){
            w.textContent="Width"+window.innerWidth;
            h.textContent="Height"+window.innerHeight;

            
        }
    </script>
</body>
</html>
