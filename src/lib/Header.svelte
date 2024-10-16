<script>
    export let headingTitle;
</script>
    

<style>
    .menu {
      position: absolute;
      top: 20px;
      right: 20px;
      background-color: lightgray;
      padding: 10px;
      border-radius: 5px;
    }
  </style>

<header>
    <h1>{headingTitle}</h1>
    <nav class="menu">
        <ul>
            <li><a href="/">Home</a></li>
            <li><a href="/about">About</a></li>
            <li><a href="/contact">Contact</a></li>
        </ul>
    </nav>
</header>

