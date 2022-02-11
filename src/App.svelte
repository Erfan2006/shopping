<!-- App.svelte -->
<script>
    import { Router, Link, Route } from "svelte-routing";
    import productList from "./prouductList.svelte";
    import About from "./routes/About.svelte";
    import Blog from "./routes/Blog.svelte";
  
    export let url = "";
  </script>
  
  <Router url="{url}">
    <nav>
      <Link to="/">Home</Link>
      <Link to="about">About</Link>
      <Link to="blog">Blog</Link>
    </nav>
    <div>
      <Route path="blog/:id" component="{BlogPost}" />
      <Route path="blog" component="{Blog}" />
      <Route path="about" component="{About}" />
      <Route path="/"><productList /></Route>
    </div>
  </Router>
