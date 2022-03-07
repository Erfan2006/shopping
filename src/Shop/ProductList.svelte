<script>


    import { navigate } from "svelte-routing";
    
    function navigateToProductList(){
    
        navigate("/products"); 
    
        
    }


    import Navigation from "./NavigationBar.svelte"
    import Product from "./Product.svelte"
    


    
    </script>
    
    <Navigation />
    <Product />


    
    <button type="button">Click</button>
    
    <button on:click="{navigateToProductList}"> Click me</button>



    
    <style>
    
    






    
    </style> 
