<!-- App.svelte -->
<script>
    import { Router, Link, Route } from "svelte-routing";
import Mainpage from "./Cart/Mainpage.svelte";
    import ProductList from "./Home/ProductList.svelte";
    export let url = "";
  </script>
  
  <Router url="{url}">
    <div>
      <Route path="/products" component="{ProductList}" />
      <Route path="/" component="{Mainpage}" />
    </div>
  </Router>

  




