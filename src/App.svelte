<script>
	import Navigation from "./NavigationBar.svelte"
	import Header from "./Header.svelte"
	import Cart from "./Product.svelte"
	
	</script>



<Navigation />
<Header />


<div class="gallery">

<Cart />
<Cart /> 
<Cart /> 

</div>





<style>
	

      
	
    
      .gallery{
      
      display: flex;
      flex-wrap: wrap;
      width: 100%;
      justify-content: right;
      align-items: right;
      
      }


	</style>
