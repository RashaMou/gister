<script>
  import Fa from "svelte-fa";
  import { faPlusSquare } from "@fortawesome/free-solid-svg-icons";
  import { faCog } from "@fortawesome/free-solid-svg-icons";
</script>

<div class="container">
  <form>
    <input
      type="text"
      id="name"
      name="name"
      required
      minlength="4"
      maxlength="8"
      size="10"
      class="search"
    />
  </form>
  <div class="icon">
    <Fa icon={faPlusSquare} />
  </div>
  <div class="icon">
    <Fa icon={faCog} />
  </div>
</div>

<style>
  .container {
    display: flex;
    align-items: flex-end;
  }
  form {
    width: 100%;
  }
  .search {
    height: 2rem;
    width: 100%;
    margin-right: 20px;
  }
  .icon {
    font-size: 2.3rem;
    margin: 20px 0 0 15px;
  }
</style>
