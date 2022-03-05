It's a holographic spinny CSS border that I couldn't find that anybody else had made and published for free!  Here you go!  Lookie! :>

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
