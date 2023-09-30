<script>
  import Navbar from "./Navbar.svelte";


</script>

<div class="body">
    <Navbar />
    <div class="container">
        <slot />
    </div>
</div>

<style>
  .body {
    font-family: "Montserrat", -apple-system, BlinkMacSystemFont, "Segoe UI",
      Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif,
      "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol",
      "Noto Color Emoji";
  }

  .container {

    display: flex;
  }

  
</style>
