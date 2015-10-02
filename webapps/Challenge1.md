### Challenge 1: Build a Static Webpage
The first thing you should learn is how to build a beautiful, useful static web page.

*A web page is a single html5 document.*

You will create a project folder and create an `index.html` file inside it.

1. In your terminal, run `mkdir MyStaticSite`
2. Run `cd MyStaticSite` to enter the project folder
3. Run `touch index.html` to create the `index.html` file
4. Run  `python -m SimpleHTTPServer` while inside `MyStaticSite/`
5. If you see `Serving HTTP on 0.0.0.0 port 8000 ...`, point your browser to the following address `0.0.0.0:8000` or `localhost:8000`

You now have an empty web page!

6. Go to getbootstrap.com to download Twitter Bootstrap
7. If you find 3 folders `css`, `fonts` and `js`, copy them into `MyStaticSite/`
8. Now, copy and paste the following code into `index.html`:
    ```
    <!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->
    <title>Bootstrap 101 Template</title>

    <!-- Bootstrap -->
    <link href="css/bootstrap.min.css" rel="stylesheet">

    <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
    <!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
      <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
    <![endif]-->
  </head>
  <body>
    <!-- CONTENT STARTS HERE -->
    <h1>Hello, world!</h1>
    <!-- CONTENT ENDS HERE -->

    <!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
    <!-- Include all compiled plugins (below), or include individual files as needed -->
    <script src="js/bootstrap.min.js"></script>
  </body>
</html>
    ```
9. Refresh your browser, or point it to `0.0.0.0:8000` or `localhost:8000`
10. If you see a beautifully rendered `Hello World!` you've made it!
