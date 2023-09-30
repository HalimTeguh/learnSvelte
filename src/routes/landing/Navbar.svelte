<script>
  import { page } from "$app/stores";

  $: routeId = $page.route.id;
</script>

<nav>
  <div class="container">
    <h1>Halim Teguh Saputro</h1>

    <ul>
      <li><a class="{(routeId === '/landing') ? 'active' : ''}" href="/landing">Home</a></li>
      <li><a class="{(routeId === '/landing/contact') ? 'active' : ''}" href="/landing/contact">Contact</a></li>
      <li><a class="{(routeId === '/landing/about') ? 'active' : ''}" href="/landing/about">About</a></li>
      <li><a class="" href="/login">Login</a></li>
    </ul>
  </div>
</nav>

<style>
  .container {
    padding: 1.5em 15em;
    width: auto;
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
    margin: 0 1em;
  }

  a {
    text-decoration: none;
    color: white;
    font-size: 1.2em;
    font-weight: bold;
    padding: 0.5em 1em;
    border-radius: 10px;
    border: 2px solid rgb(26, 188, 156, 0);
    transition: 0.3s ease-in-out;

  }

  a.active {
    background-color: #1abc9c;
    color: #2c3e50;
  }
  a.active:hover {
    color: #2c3e50;
  }

  a:hover {
    border: 2px solid rgb(26, 188, 156);
    color: rgb(26, 188, 156);
  }
</style>
