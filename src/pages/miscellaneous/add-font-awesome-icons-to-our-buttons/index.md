---
title: Add Font Awesome Icons to Our Buttons
---
Font Awesome is a convenient library of icons. These icons are vector graphics, stored in the .svg file format. These icons are treated just like fonts. You can specify their size using pixels, and they will assume the font size of their parent HTML elements.

Heres how you add an icon:

```
<i class="fa fa-thumbs-up"></i>
```

Here is how you would insert that icon on to a button:

```
<button class="btn btn-block btn-primary"><i class="fa fa-thumbs-up"></i> Like</button>
```

Change icon size:

```
<i class="fa fa-thumbs-up fa-4px"></i>
```

You can also rotate the icons:

```
<i class="fa fa-thumbs-up fa-rotate-90"></i>
```

Icons can be stacked, here a thumbs up in a square:

```
<span class="fa-stack fa-lg">
  <i class="fa fa-square-o fa-stack-2x"></i>
  <i class="fa fa-thumbs-up fa-stack-1px"></i>
</span>
```

With fa-spin, icons will rotate, works well with spinner or cog:

```
<i class="fa fa-spinner fa-spin fa-3x fa-fw"></i>
<span class="sr-only">Loading...</span>
```

#### More Information:

Get font awesome on your website:
[Font awesome - Get started](http://fontawesome.io/get-started/)

Check out all the available font awesome icons:
[Icons](http://fontawesome.io/icons/)
