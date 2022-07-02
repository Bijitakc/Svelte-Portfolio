<script>
  import Nav from './components/Nav.svelte'
  import Socials from './components/Socials.svelte'
  import Home from './components/Home.svelte'
</script>

<svelte:head>
  <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Josefin+Slab&display=swap" rel="stylesheet">
</svelte:head>

<div class="container">
  <Socials />
  <Nav />
  <div class="content-page">
    <Home />
  </div>
</div>

<style>
  :root {
    font-family: 'Josefin Slab', serif;
  }
  .container {
    padding: 1em;
    margin: 0 auto;
  }
  .content-page {
    float: right;
    height: 676px;
    width: calc(100% - 70px);
  }
</style>
