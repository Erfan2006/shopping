<script>
	import Navigation from "./NavigationBar.svelte"
	import Header from "./Header.svelte"
	import Cart from "./Product.svelte"
	import Banner from "./Centerbanner.svelte"
	</script>



<Navigation />
<Header />



<div class="gallery">

<Cart />
<Cart /> 
<Cart /> 
<Cart />
<Cart /> 
<Cart />
<Cart /> 
<Cart />

</div>

<Banner	 />










<style>


@font-face {
		font-family: 'iranSans';
		src: url("./IRANSansWeb_Medium.ttf") format("ttf");
		font-style: normal;
	}
	
    
      .gallery{
      
      display: flex;
      flex-wrap: wrap;
      width: 100%;
      justify-content: right;
      align-items: right;
      
      }



	</style>
