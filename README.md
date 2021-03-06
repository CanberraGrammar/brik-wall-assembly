# Brik Wall Construction App

This simple web app is designed to help you construct a Brik / Lego wall from a design which you export from Photoshop. For full instructions on how to prepare the design, see our blog post at http://codecadets.blog

## Instructions

We have included our Brik wall design so that you can see how the app works before importing your own design.

When you are ready to bring across your design, replace all the images in the `images` folder with the slices of your design. Then, find the following section in the `app.html` file and edit the variables to match your design:

```javascript
/* CHANGE THESE VARIABLES TO SET THE HEIGHT AND WIDTH OF YOUR DESIGN (IN TERMS OF NUMBER OF TILES) */

var tilesHorizontal = 10; // 10 tiles across
var tilesVertical = 12; // 12 tiles down

// So, 120 tiles in total

// For example, if the slices are named brik-wall_01.jpg, brik-wall_02.jpg, etc. then the filename
// prefix would be "brik-wall". Do not include the underscore _ in the prefix.
var fileNamePrefix = "brik-wall";
```

That's it. This is a pretty simple script, so if you have any suggestions for improvement then please log an issue or (even better) fork this repo and then submit a pull request!