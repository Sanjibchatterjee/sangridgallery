# Sangrid Gallery
## Pure CSS Responsive Image Grid

Now create any number of columns on any range of devices! Yes you can create 1, 2, 3, 4, 5, 6, 7, ....12 without need to custom code for any odd or even number of columns in range of 12 columns.
Pure CSS based grid to display images as gallery. Whether you are building an image gallery for artistic site/ app or albums or making product picture for e-commerce site this grid will be equally useful.
This grid can be used with any of your existing framework if any like bootstrap or foundation.

## How to Use?
1. Download the css [sangridgal.min.css](https://github.com/Sanjibchatterjee/sangridgallery/blob/master/sangridgal.min.css) 

2.Place the "grid" div inside any of your existing html structure or div and follow this following structure.

```
<div class="grid">
<div class="sanwrapper">
<div class="sancol ">
 <div class="item"><img src="img/01.jpg" class="img_resp">   </div>
 <div class="item">....</div>
<div class="item">....</div>
</div>
</div>
</div>
```

###### Available classes for different sizes are as follows-

Device pointer | Resolutions | Columns | Classes
------------ | ------------- | ------------- | -------------
xs | 420px or lower | 1-12 | sanxscol1 - sanxscol12
sm | 421px - 770px | 1-12 | sansmcol1 - sansmcol12
me | 771px - 920px | 1-12 | sanmecol1 - sanmecol12
la | 921px - 1100px  | 1-12 | sanlacol1 - sanlacol12
xl | 1101px to higher | 1-12 | sanxlcol1 - sanxlcol12

**"sancol"** is the default class where main column numbers are defined. Automatically it will create a 5 column fluid and responsive picture grid for devices with size xl  and will reduce to 4 columns for la-, 3 columns for me-, 2 columns for sm- and 1 column for xs-.
If you want to customize the number of columns you need to add class with corresponding column number.
There are total 12 grids and each grid is represented with the number together with the device size.
For example if we want 2 columns for devices under xs category the class name should be-
**sanxscol2** and can be added just after **"sancol"** in html - ```<div class="sancol  sanxscol2 "></div>```
Similarly if you need a 4 column gallery for devices under **la** category the code will be-
```<div class="sancol  sanlacol4 "></div> ```
If we require 9 number of columns for devices beyond **xl** ie more than 1300px the html can be-
```<div class="sancol  sanxlcol9"></div> ```

## Live Example: [Sangrid Gallery](http://sanjibchatterjee.com/sangrid)
