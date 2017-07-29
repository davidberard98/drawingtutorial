# Making Buttons

We're going to need 2 kinds of buttons:

1. [Color buttons](#colorbuttons)
2. [Tool buttons](#toolbuttons) (eraser, marker, paint bucket)

<a name="colorbuttons"></a>
## Color buttons

First let's make a **container** to go around the buttons.

- Put the following code **below the image tag from before**

```html
    <div id="colorContainer">
    
    
    </div>
```

- Now get your color images.  (If you haven't already made them, go to [pixlr.com](http://pixlr.com) and make one for each color you desire).  For each one, make sure you have **rgb values**

(If you don't have the rgb values yet, use [this tutorial for finding RGB values](./4.1-RGB.md) )

Figure out **where your color images are**.  Remember to include the folder name when you write the `src` for your images.

Now, **inside** the `div` we just created, include the images **in the following format**:

```html
      <img src="[path to image]" data-r="[r value]" data-g="[g value]" data-b="[b value]" />
```

Remember to replace [path to image] with the actual folders and file name of your color swatch image, and also replace r value, g value, and b value with your actual RGB values.

**Do this for all your color swatches**


<a name="toolbuttons"></a>
## Tool Buttons

Find some images you like for a pen/pencil, eraser, and paintbucket.

We're going to do something similar. Start with a container div which will go after the colorContainer div (or before, if you prefer).

```html
    <div id="toolContainer">
      
    </div>
```

Now include your images in the following format, into the toolContainer div.:

```html
      <img src="[pen image path]" id="pen" />
      <img src="[paintbucket image path]" id="paintbucket" />
      <img src="[eraser image path]" id="eraser" />
```

**Once you are done** you can move on to [Making the code functional](./5-UsingDrawing.js.md)