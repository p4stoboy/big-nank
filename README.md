# BIG NANK

I have left comments throughout the html file to try and demonstrate what is happening.

The only issue with this approach is that every time you add new images to the images folder 
you need to edit `images.js` and add the new filenames to the array.

The alternative is to pull a random file from an image platform 
(more code, less reliable results), or run a small server that can automatically generate
an array of image paths every time the page loads (so you could just drop new images in without
maintaning `images.js`).

Once you have your head around this approach it will be simple enough to expand on it 
either way.

![nank](https://media.giphy.com/media/h8eHp71bqXlN3BSYjh/giphy.gif)