[![N|Solid](https://gourl.io/images/logo.png)](https://gourl.io/)
[https://gourl.io](https://gourl.io/)


# How to Isolate Bootstrap CSS to Avoid Conflicts

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

And use any css style from folder css4.1 like
```html
<head>
<link rel="stylesheet" href="css4.1/bootstrapcustom.min.css" crossorigin="anonymous">
...
</head>
```

Done!


## Isolate Bootstrap 4.1 CSS Styles in folder css4.1

- bootstrapcustom.min.css - default bootstrap isolate 4.1 style, https://getbootstrap.com/docs/4.1/examples/pricing/
- cerulean.min.css - isolate css based on https://bootswatch.com/cerulean/
- darkly.min.css - isolate css https://bootswatch.com/darkly/
- flatly.min.css - isolate css https://bootswatch.com/flatly/
- litera.min.css - isolate css https://bootswatch.com/litera/
- lux.min.css - isolate css https://bootswatch.com/lux/
- minty.min.css - isolate css https://bootswatch.com/minty/
- pulse.min.css - isolate css https://bootswatch.com/pulse/
- sandstone.min.css - isolate css https://bootswatch.com/sandstone/
- sketchy.min.css - isolate css https://bootswatch.com/sketchy/
- solar.min.css - isolate css https://bootswatch.com/solar/
- superhero.min.css - isolate css https://bootswatch.com/superhero/
- united.min.css - isolate css https://bootswatch.com/united/

  