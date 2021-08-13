<script>
  import Fa from "svelte-fa";
  import { faLaptop } from "@fortawesome/free-solid-svg-icons";
  import { faGithub } from "@fortawesome/free-brands-svg-icons";
</script>

<div class="sidebar">
  <h2>NOTES</h2>
  <div class="local">
    <h3>Local</h3>
    <div class="icon">
      <Fa icon={faLaptop} />
    </div>
  </div>
  <div class="gists">
    <h3>Gists</h3>
    <div class="icon">
      <Fa icon={faGithub} />
    </div>
  </div>

  <h2>LANGUAGES</h2>
</div>

<style>
  .sidebar {
    width: 250px;
    height: 100vh;
    padding: 30px 0 0 30px;
    margin-right: 30px;
  }

  .local,
  .gists {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 20px;
    padding: 10px;
    border-radius: 3px;
  }

  .local:hover,
  .local:active,
  .gists:hover,
  .gists:active {
    background-color: rgb(20, 90, 94);
    color: white;
  }

  h2 {
    margin-bottom: 20px;
    font-weight: bolder;
    font-size: 1.2rem;
  }
</style>
