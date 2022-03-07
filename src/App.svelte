<!-- App.svelte -->
<script>
  import { Router, Link, Route } from "svelte-routing";
  import Mainpage from "./Home/Mainpage.svelte";
  import ProductList from "./Home/ProductList.svelte";
  import dropdownshopping from "./Home/dropdownshopping.svelte";
  export let url = "";
</script>

<Router url="{url}">
  <div>
    <Route path="/products" component="{ProductList}" />
    <Route path="/" component="{Mainpage}" />
    <Route path="/" component="{ dropdownshopping }"/>
  </div>
</Router>
