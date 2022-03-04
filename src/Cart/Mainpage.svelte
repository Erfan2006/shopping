<script>



import { navigate } from "svelte-routing";

function navigateToProductList(){

    navigate("/products"); 

    
}


</script>


<button type="button">Click</button>

<button on:click="{navigateToProductList}"> Click me</button>


<style>



</style>
