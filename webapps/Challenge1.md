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

### Lecture
I'll just link to the countless resources on HTML5 out there for your reading pleasure. If you didn't understand anything that happened in this challenge, you're better off reading through all the provided links until you come to a general understanding of what HTML is, where CSS plays a role and what JavaScript is doing under the covers too.

Ultra Beginner Introduction: http://www.htmlgoodies.com/primers/html/article.php/3478131

Not Beginner Friendly, but you'll quickly learn to love Mark: http://diveintohtml5.info/past.html

If you didn't get the `python -m SimpleHTTPServer` command, I'll explain it shortly. If it worked, you just started a server. Web sites (and web pages) are *served* to the user's browser by a web server. By running that command and naming your web page `index.html`, you created and run a simple web server.

Every web server needs an address to run on (the same address your browser navigates to) and a port on that address to listen to. Your address was `0.0.0.0` and your port number was `8000`. Yes, that first one was an IP Address; Your local IP Address. The second one was an open port on your computer that the `SimpleHTTPServer` was listening on.

Any computer in the world that has your computer's actual IP Address could send a request to that port and say hello to your own little web server. Congratulations, you're contributing to the Internet!
