<!-- App.svelte -->
<script>
    import { Router, Link, Route } from "svelte-routing";
    import ProductList from "./Home/ProductList.svelte";
    export let url = "";
  </script>
  
  <Router url="{url}">
    <div>
      <Route path="/" component="{ProductList}" />
    </div>
  </Router>