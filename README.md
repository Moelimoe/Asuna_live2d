# Asuna_live2d
#Asuna live2d model
#With a succinct code to realize a live2d model on your page like this:

<html class="windows desktop landscape"><head>
        <meta name="live2DWidget" charset="utf-8">
    <script type="text/javascript" charset="utf-8" async="" src="http://localhost:8088/lib/L2Dwidget.0.min.js"></script></head>
        <body>
        <script src="./lib/L2Dwidget.min.js"></script>
        <script>
            L2Dwidget.init({
                model:{jsonPath:"./assets/asuna_04.model.json"}
            });
        </script>
        

<div id="live2d-widget"><canvas id="live2dcanvas" width="300" height="600" style="position: absolute; opacity: 1.0;left:0px; bottom: -20px; z-index: 99999; pointer-events: none;"></canvas></div></body></html>
