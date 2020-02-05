[![N|Solid](https://gourl.io/images/logo.png)](https://gourl.io/)
.

[https://gourl.io](https://gourl.io/)
.


# How to Isolate Bootstrap 4.4.1 CSS to Avoid Conflicts

Bootstrap is the most popular CSS framework on the web. It makes it incredibly easy to create beautiful, responsive designs that just work. 
However, it’s not always possible to use Bootstrap for your entire website. Often the website’s main CSS is outside of your control. 
You just need to use a portion of Bootstrap CSS. 


**Based on instruction - https://formden.com/blog/isolate-bootstrap** (compile with [LESS](http://lesscss.org/))


## Usage

To use Bootstrap CSS, simply wrap your HTML in a div with the class bootstrapiso, like so:

```html
<div class="bootstrapiso">
<!-- Any HTML here will be styled with Bootstrap CSS -->
</div>
```

And use any css style from folder css4.1 like so:
```html
<head>
<link rel="stylesheet" href="css4.1/bootstrapcustom.min.css" crossorigin="anonymous">
...
</head>
```

Done!
 
.


## Empty Bootstrap4 page example - 
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="description" content="">
    <title>Page1</title>

    <!-- Isolated Bootstrap4.4.1 CSS - -->
    <link rel="stylesheet" href="css4.1/bootstrapcustom.min.css" crossorigin="anonymous">   

    <!-- JS -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.4.1/jquery.min.js" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" crossorigin="anonymous"></script>
    <script defer src="https://use.fontawesome.com/releases/v5.12.0/js/all.js" crossorigin="anonymous"></script>


  </head>

  <body>

  <div class="bootstrapiso">
  <!-- Any HTML here will be styled with Bootstrap CSS -->
  </div>

  </body>
</html>
```
 
.
   
.
 

## Isolated Bootstrap 4.4.1 CSS Styles in folder css4.1

- bootstrapcustom.min.css - default bootstrap 4.4.1 isolated style, demo https://getbootstrap.com/docs/4.1/examples/pricing/
- cerulean.min.css - isolated css based on https://bootswatch.com/cerulean/
- darkly.min.css - isolated css https://bootswatch.com/darkly/
- flatly.min.css - isolated css https://bootswatch.com/flatly/
- litera.min.css - isolated css https://bootswatch.com/litera/
- lux.min.css - isolated css https://bootswatch.com/lux/
- minty.min.css - isolated css https://bootswatch.com/minty/
- pulse.min.css - isolated css https://bootswatch.com/pulse/
- sandstone.min.css - isolated css https://bootswatch.com/sandstone/
- sketchy.min.css - isolated css https://bootswatch.com/sketchy/
- solar.min.css - isolated css https://bootswatch.com/solar/
- superhero.min.css - isolated css https://bootswatch.com/superhero/
- united.min.css - isolated css https://bootswatch.com/united/
   
 