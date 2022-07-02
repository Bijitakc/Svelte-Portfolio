<script>
  import Router from "svelte-spa-router";
  import ProjectsPage from './routes/ProjectsPage.svelte';
  import NotFound from './routes/NotFound.svelte';
  import Nav from "./routes/Nav.svelte";
  import Socials from './routes/Socials.svelte';
  import Home from "./routes/Home.svelte";

  let routes = {
    "/": Home,
    "/projects": ProjectsPage,

    "*": NotFound
  }
</script>

<svelte:head>
  <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Josefin+Slab&display=swap" rel="stylesheet">
</svelte:head>

<div class="container">
  <Socials />
  <Nav />
</div>

<main>
  <Router {routes}></Router>
</main>

<style>
  :root {
    font-family: 'Josefin Slab', serif;
  }
  .container {
    padding: 1em;
    margin: 0 auto;
  }
</style>
