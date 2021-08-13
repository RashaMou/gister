<script>
  import Header from "./components/Header.svelte";
  import Sidebar from "./components/Sidebar.svelte";
  import Search from "./components/Search.svelte";
  import Content from "./components/Content.svelte";
</script>

<svelte:head>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link
    href="https://fonts.googleapis.com/css2?family=Source+Sans+Pro:wght@200&display=swap"
    rel="stylesheet"
  />
</svelte:head>

<Header />
<div class="wrapper">
  <Sidebar />
  <div class="main">
    <Search />
    <Content />
  </div>
</div>

<style>
  :global(body, img, h1, h2, h3, div) {
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    font: inherit;
    vertical-align: baseline;
    font-family: "Source Sans Pro", sans-serif;
    box-sizing: border-box;
  }
  .wrapper {
    display: flex;
  }
  .main {
    width: 75%;
    padding: 0 25px 0 25px;
  }
</style>
