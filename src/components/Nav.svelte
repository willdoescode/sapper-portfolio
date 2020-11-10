<script>
  export let segment;
</script>

<style>
  nav {
    font-weight: 300;
    padding: 0 1em;
  }

  ul {
    margin: 0;
    padding: 0;
  }

  /* clearfix */
  ul::after {
    content: "";
    display: block;
    clear: both;
  }

  li {
    display: block;
    float: right;
  }

  [aria-current] {
    position: relative;
    display: inline-block;
  }

  [aria-current]::after {
    position: absolute;
    content: "";
    width: calc(100% - 1em);
    height: 2px;
    background-color: goldenrod;
    display: block;
    bottom: -1px;
  }

  a {
    text-decoration: none;
    padding: 1em 0.5em;
    color: goldenrod;
    display: block;
    font-family: "Fira Code";
    font-weight: 700;
    margin: 0 0 0.5em 0;
    background-color: #f3ec78;
    background-image: linear-gradient(45deg, #f3ec78, #af4261);
    background-size: 100%;
    -webkit-background-clip: text;
    -moz-background-clip: text;
    -webkit-text-fill-color: transparent;
    -moz-text-fill-color: transparent;
  }

  a:hover {
    color: #f3ec78;
  }
</style>

<nav>
  <ul>
    <div>
      <li>
        <a
          aria-current={segment === 'interests' ? 'page' : undefined}
          href="interests">Interests</a>
      </li>
      <li>
        <a
          aria-current={segment === 'career' ? 'page' : undefined}
          href="career">Career</a>
      </li>
      <li>
        <a
          aria-current={segment === undefined ? 'page' : undefined}
          href=".">Home</a>
      </li>
    </div>
  </ul>
</nav>
