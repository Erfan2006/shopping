<script>



import { navigate } from "svelte-routing";

function navigateToProductList(){

    navigate("/productList"); 

    
}


</script>


<button type="button">Click</button>

<button on:click="{navigateToProductList}"> Click</button>


<style>



</style>