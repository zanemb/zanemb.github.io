<html>
  <head>
    <link rel="stylesheet" href="https://pyscript.net/latest/pyscript.css" />
    <script defer src="https://pyscript.net/latest/pyscript.js"></script>
  </head>
  
  <body>
    <p id="text"></p>
    <py-script>
      print("Hello World")
      x = 0
      pyscript.write("text", x + 1)
    </py-script>
  </body>
</html>

<!--
## Home
<div class="position-relative overflow-hidden p-3 p-md-5 m-md-3 text-center bg-dark" style="color:white">
    <img class="mb-4" src="IMG_1187.jpeg" alt="">
    <div class="col-md-6 p-lg-1 mx-auto my-2">
        <h1 class="display-4 font-weight-normal">Z's Test Website</h1>
        <p class="lead font-weight-normal">Begin by clicking the link below</p>
        <a class="btn btn-primary" href="{{ url_for('market_page') }}">Begin</a>
    </div>
    <div class="product-device box-shadow d-none d-md-block"></div>
    <div class="product-device product-device-2 box-shadow d-none d-md-block"></div>
</div>
-->
