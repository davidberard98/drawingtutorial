# 2 - Other Setup:Including Files, Making Styles

## Including Files

There's a file we need to download called `drawing.js`.  This contains the code that actually allows us to draw.

You should be able to get it [here](./drawing.js).  Download it and then put it in the **same folder as your html file**

This is going to *include javascript*.  In order to avoid making the body messy, we can put this inside the head with the following code

```html
    <script src="drawing.js"></script>
```

## Making Styles

Remember that **HTML** makes the structure of the page and **CSS** changes how it looks.

Right after the `<title></title>` tags, write this code:

```html
    <style>
    
    
    
    </style>
```

Now we can test some CSS in here!  Here's one idea:  **change the background color**

To do it, this is the code we need:

```css
      body {
        background-color: #2F489D;
      }
```

If you want to choose a different color, go to [htmlcolorcodes.com](http://htmlcolorcodes.com/) to find the right color code.

Once you're done, go to the next section: [3 - Include Image](./3-IncludeImage.md)