## Code Snippets for APEX Banner Image Creation Video

- Banner images in this example should be 1920x320. Please see the example images in git repo. 

- Core HTML Code

```
<div class="banner img_1">
<div class="cover">
<div class="banner_text">
Collect Data, Adjust Drills, Improve Player Performance
</div>
</div>
</div>
```

- Page Level APEX CSS
```
.teamActionButton {
height: 120px;
width: 200px;
font-size: 1.9rem;
margin: .2rem 3rem .2rem 3rem;
line-height: 3rem;
}

.banner{
min-height: 320px;
}

.cover{
background: url(#APP_IMAGES#ball_overlay.png);
background-repeat: repeat;
min-height: 320px;
}

.img_1{
  background: url(#APP_IMAGES#banner_1.jpg);
  background-repeat: no-repeat;
  background-size: auto;
}

.img_2{
  background: url(#APP_IMAGES#banner_2.jpg);
  background-repeat: no-repeat;
  background-size: auto;
}

.img_3{
  background: url(#APP_IMAGES#sliding_image_3.jpg);
  background-repeat: no-repeat;
  background-size: auto;
}

.img_3{
  background: url(#APP_IMAGES#20210418_135411.02_21_01_07.Still002.png);
  background-repeat: no-repeat;
  background-size: auto;
}

.t-Body-contentInner{
padding:0;
}


.banner_text{
margin: auto;
font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Oxygen,Ubuntu,Cantarell,"Fira Sans","Droid Sans","Helvetica Neue",sans-serif;
    width: 60%;
    text-align: center;
     font: 600 3.3em cookie;
    text-align: center;
    filter: invert(1) grayscale(1) contrast(9) drop-shadow(.05em .05em black);
    padding-top: 120px;
}

```
