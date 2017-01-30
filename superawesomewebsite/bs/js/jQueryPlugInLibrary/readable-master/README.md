# Readable

![readable in action](https://s3.amazonaws.com/f.cl.ly/items/081k1i0l1G1s090b2t2W/readable.gif)

Readable is a small jQuery plugin to help you make your paragraphs, well, more readable. It injects styling between the 45th and 75th character of every `<p>` tag on your page.

This gives you a visual reference to tell you if tweaks are needed on your font-size or content width, etc.

Read why the 45-75 rule is important and [view the demo here](http://mds.sh/readable).

## Implementation Using jQuery
There are 3 files required to get **Readable** working on your site.
2 of them are inside the **readable** folder and the other is jQuery.

1. readable.css *(2 kilobytes)*
2. readable.js *(794 bytes)*
3. jQuery ( https://ajax.googleapis.com/ajax/libs/jquery/2.1.3/jquery.min.js )


Put **readable.css** before your closing `</head>` and **jQuery** and **readable.js** just before your closing `</body>`

```html
<html>
  <head>
    <title>Your Website</title>
    <!-- readable styles -->
    <link rel="stylesheet" href="readable/readable.css">
  </head>
  <body>
    <!-- your website here -->
    <!-- readable scripts -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
    <script type="text/javascript" src="readable/readable.js"></script>
  </body>
</html>
```

## Implementation Using Vanilla JavaScript
Only 2 files required to get **Readable** working on your site.
They are inside the **readable** folder.

1. readable.css *(2 kilobytes)*
2. readable-vanilla.js *(1 kilobyte)*


Put **readable.css** before your closing `</head>` and **readable-vanilla.js** just before your closing `</body>`

```html
<html>
  <head>
    <title>Your Website</title>
    <!-- readable styles -->
    <link rel="stylesheet" href="readable/readable.css">
  </head>
  <body>
    <!-- your website here -->
    <!-- readable script -->
    <script type="text/javascript" src="readable/readable-vanilla.js"></script>
  </body>
</html>
```

Thanks to [Jon Suh](http://github.com/jonsuh) for the vanilla flavor!

## Bookmarklet
I started tinkering with a bookmarklet, but it doesn't work yet. Feel free to fork it and get it working. :)
