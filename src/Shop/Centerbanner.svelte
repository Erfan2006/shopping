<script>



</script>


<div class="banner"> 
  <img src="assets/images/Banner.jpg"/>
  <a class="text" href="url">Go to Shopping !</a>
</div>




<style>



.banner {
  display: flex;
  position: relative;
  padding-top: 28px;
}
.banner img{
  width: 100%;

}
.text{
color: rgb(255, 255, 255) ;
font-size: 40px;
padding-left: 150px;
text-decoration: none;
position: absolute;
width: 100%;
height: 100%;
display: flex;
justify-content: left;
align-items: center;
}


@media screen and (max-width: 991px) {

  .text{
    font-size: 30px;
    padding-left: 40px;
  }

}

@media screen and (max-width: 767px) {

  .text{
    font-size: 20px;
    padding-left: 20px;
  }

}

@media screen and (max-width: 479px) {

  .text{
    font-size: 30px;
    padding-left: 20px;
  }

}
    
</style>