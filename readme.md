It's a holographic spinny CSS border that I couldn't find that anybody else had made and published for free!  Here you go!  Lookie! :>

The CSS:
```
<style>
      .parent {
        position: relative;
		z-index: 1;
        top: 0;
        left: 0;
      }
      .image1 {
        position: relative;
		z-index: 2;
        top: 0;
        left: 0;

      }
      .image2 {
        position: absolute;
		z-index: 3;
        top: 15px;
        left: 15px;
      }  
	  .image3 {
        position: absolute;
		z-index: 4;
        top: 30px;
        left: 20px;
      }
	.speen {
    -webkit-animation:spin 12s linear infinite;
    -moz-animation:spin 12s linear infinite;
    animation:spin 12s linear infinite;
}
@-moz-keyframes spin { 
    100% { -moz-transform: rotate(360deg); } 
}
@-webkit-keyframes spin { 
    100% { -webkit-transform: rotate(360deg); } 
}
@keyframes spin { 
    100% { 
        -webkit-transform: rotate(360deg); 
        transform:rotate(360deg);   
	  
    </style>
```

The HTML:
```
    <div class="parent" style="background:url('holo.jpg'); height: 391px; max-width: 391px; border-radius: 50%;">
      <img class="image1 speen" style="background:url('holo.jpg'); height: 391px; max-width: 391px; border-radius: 50%;" src="holo.jpg" />
	  <img class="image2" style="width: 361px; height: 361px; background: url('lhowon.jpg'); border-radius: 50%;">
      <img class="image3" src="icze4r.png" style="border-radius: 50%; width: 350px;" />
    </div>
```
Parent really doesn't need to have anything in the 'style' portion, I don't think. Oh well! :3c
Image1 is the holographic ring background, it moves! :> (holo.jpg, which was from Pixabay, so it's free... we hope)
Image2 is the background behind the icon of the person. (lhowon.jpg)
Image3 is the icon! You might have to move it a little bit (see: left: 20px or whatever), but as long as it's about 391px, you'll be fine! :>

NO THIS ISN'T RESPONSIVE

WHAT, DO YOU WANT THE WORLD

JEEEEEEEEEEEEZUMS

Check out https://icze4r.github.io/holographic-spinny-icon/index.html if you want to see it in action :3c
