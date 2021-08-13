<script>
  import Fa from "svelte-fa";
  import { faCode } from "@fortawesome/free-solid-svg-icons";
</script>

<header class="header">
  <div class="icon">
    <Fa icon={faCode} />
  </div>
  <h1>Gister</h1>
</header>

<style>
  .header {
    background-color: rgb(20, 90, 94);
    height: 100px;
    display: flex;
    justify-content: center;
  }
  .icon {
    width: 75px;
    margin: 10px 0 10px 20px;
    color: white;
    font-size: 4rem;
  }
  h1 {
    font-size: 3rem;
    color: white;
    font-weight: bolder;
    margin: 20px 0 0 10px;
  }
</style>
