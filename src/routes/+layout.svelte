<script>
</script>

<div class="body">
  <nav>
    <div class="container">
      <h1>Halim Teguh Saputro</h1>

      <ul>
        <li><a class="active" href="/">Home</a></li>
        <li><a class="" href="/about">About</a></li>
        <li><a class="" href="/contact">Contact</a></li>
      </ul>
    </div>
  </nav>

  <slot />
</div>

<style>
  .body {
    font-family: "Montserrat", -apple-system, BlinkMacSystemFont, "Segoe UI",
      Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif,
      "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol",
      "Noto Color Emoji";
  }

  .container {
    padding: 1.5em 15em;
    display: flex;
  }

  nav {
    background-color: #2c3e50;
    color: white;
  }
  h1 {
    margin: 0;
    font-size: 1.5em;
  }

  ul {
    display: flex;
    list-style: none;
    margin: 0;
    margin-left: auto;
  }

  li {
    margin-right: 2em;
  }

  a {
    text-decoration: none;
    color: white;
    font-size: 1.2em;
    font-weight: bold;
  }

  a.active {
    background-color: #1abc9c;
    padding: 0.5em 1em;
    border-radius: 10px;
  }
</style>
