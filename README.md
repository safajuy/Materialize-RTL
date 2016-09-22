MaterializeCSS RTL Framwork
===

 
 * import Google Font Icons 
 * import materialize-rtl.min.css or materialize-rtl.css from CSS Folder
 * for RTL Direction in all pages, insert this code in your css. (DO NOT insert in framework CSS)
 ```CSS
 body{direction:rtl}
 ```
 
 * import jQuery before importing materialize.js!
 ```HTML
 <!DOCTYPE html>
  <html>
    <head>
      <!--Import Google Icon Font-->
      <link href="http://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
      <!--Import materialize.css-->
      <link type="text/css" rel="stylesheet" href="css/materialize-rtl.css"  media="screen,projection"/>

      <!--Let browser know website is optimized for mobile-->
      <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    </head>

    <body>
      <!--Import jQuery before materialize.js-->
      <script type="text/javascript" src="https://code.jquery.com/jquery-2.1.1.min.js"></script>
      <script type="text/javascript" src="js/materialize.min.js"></script>
    </body>
  </html>
```