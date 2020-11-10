<style>
  @import url("https://fonts.googleapis.com/css2?family=Fira+Code&display=swap");
  @import url("https://fonts.googleapis.com/css2?family=Ubuntu&display=swap");

  * {
    margin: 0;
    padding: 0;
    color: whitesmoke;
  }
  .container2 {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    margin: 10px 0 0 0;
  }

  .container2 .langs {
    margin-top: 10px;
    width: 480px;
  }
  .container {
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    flex-direction: column;
  }

  .langs {
    background-color: lightgoldenrodyellow;
    border-radius: 15px;
    padding: 10px;
  }

  .head {
    font-size: 2em;
    font-family: "Lora";
    text-transform: uppercase;
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

  .interest {
    font-family: "Lora";
    background-color: #f3ec78;
    background-image: linear-gradient(45deg, #f3ec78, #af4261);
    background-size: 100%;
    -webkit-background-clip: text;
    -moz-background-clip: text;
    -webkit-text-fill-color: transparent;
    -moz-text-fill-color: transparent;
  }

  .codes {
    margin-top: 20px;
  }

  .how {
    padding-top: 20px;
  }
</style>

<svelte:head>
  <title>Interests - William lane</title>
</svelte:head>
<div class="container">
  <header class="head">
    <h1>Interests</h1>
  </header>
  <h1 class="interest">Coding</h1>

  <div class="container2">
    <p class="langs">
      <a href="https://aws.amazon.com/amplify/" target="_blank">
        <img
          src="https://docs.amplify.aws/assets/logo-dark.svg"
          alt="amplify"
          width="40"
          height="40" />
      </a>
      <a href="https://babeljs.io/" target="_blank">
        <img
          src="https://www.vectorlogo.zone/logos/babeljs/babeljs-icon.svg"
          alt="babel"
          width="40"
          height="40" />
      </a>
      <a href="https://www.gnu.org/software/bash/" target="_blank">
        <img
          src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg"
          alt="bash"
          width="40"
          height="40" />
      </a>
      <a href="https://getbootstrap.com" target="_blank">
        <img
          src="https://devicons.github.io/devicon/devicon.git/icons/bootstrap/bootstrap-plain.svg"
          alt="bootstrap"
          width="40"
          height="40" />
      </a>
      <a href="https://www.w3schools.com/css/" target="_blank">
        <img
          src="https://devicons.github.io/devicon/devicon.git/icons/css3/css3-original-wordmark.svg"
          alt="css3"
          width="40"
          height="40" />
      </a>
      <a href="https://www.electronjs.org" target="_blank">
        <img
          src="https://devicons.github.io/devicon/devicon.git/icons/electron/electron-original.svg"
          alt="electron"
          width="40"
          height="40" />
      </a>
      <a href="https://expressjs.com" target="_blank">
        <img
          src="https://devicons.github.io/devicon/devicon.git/icons/express/express-original-wordmark.svg"
          alt="express"
          width="40"
          height="40" />
      </a>
      <a href="https://git-scm.com/" target="_blank">
        <img
          src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg"
          alt="git"
          width="40"
          height="40" />
      </a>
      <a href="https://golang.org" target="_blank">
        <img
          src="https://devicons.github.io/devicon/devicon.git/icons/go/go-original.svg"
          alt="go"
          width="40"
          height="40" />
      </a>
      <a href="https://graphql.org" target="_blank">
        <img
          src="https://www.vectorlogo.zone/logos/graphql/graphql-icon.svg"
          alt="graphql"
          width="40"
          height="40" />
      </a>
      <a href="https://gridsome.org/" target="_blank">
        <img
          src="https://www.vectorlogo.zone/logos/gridsome/gridsome-icon.svg"
          alt="gridsome"
          width="40"
          height="40" />
      </a>
      <a href="https://www.w3.org/html/" target="_blank">
        <img
          src="https://devicons.github.io/devicon/devicon.git/icons/html5/html5-original-wordmark.svg"
          alt="html5"
          width="40"
          height="40" />
      </a>
      <a href="https://www.invisionapp.com/" target="_blank">
        <img
          src="https://www.vectorlogo.zone/logos/invisionapp/invisionapp-icon.svg"
          alt="invision"
          width="40"
          height="40" />
      </a>
      <a href="https://www.java.com" target="_blank">
        <img
          src="https://devicons.github.io/devicon/devicon.git/icons/java/java-original-wordmark.svg"
          alt="java"
          width="40"
          height="40" />
      </a>
      <a
        href="https://developer.mozilla.org/en-US/docs/Web/JavaScript"
        target="_blank">
        <img
          src="https://devicons.github.io/devicon/devicon.git/icons/javascript/javascript-original.svg"
          alt="javascript"
          width="40"
          height="40" />
      </a>
      <a href="https://www.linux.org/" target="_blank">
        <img
          src="https://devicons.github.io/devicon/devicon.git/icons/linux/linux-original.svg"
          alt="linux"
          width="40"
          height="40" />
      </a>
      <a href="https://nextjs.org/" target="_blank">
        <img
          src="https://cdn.worldvectorlogo.com/logos/nextjs-3.svg"
          alt="nextjs"
          width="40"
          height="40" />
      </a>
      <a href="https://nodejs.org" target="_blank">
        <img
          src="https://devicons.github.io/devicon/devicon.git/icons/nodejs/nodejs-original-wordmark.svg"
          alt="nodejs"
          width="40"
          height="40" />
      </a>
      <a href="https://www.photoshop.com/en" target="_blank">
        <img
          src="https://devicons.github.io/devicon/devicon.git/icons/photoshop/photoshop-plain.svg"
          alt="photoshop"
          width="40"
          height="40" />
      </a>
      <a href="https://www.postgresql.org" target="_blank">
        <img
          src="https://devicons.github.io/devicon/devicon.git/icons/postgresql/postgresql-original-wordmark.svg"
          alt="postgresql"
          width="40"
          height="40" />
      </a>
      <a href="https://postman.com" target="_blank">
        <img
          src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg"
          alt="postman"
          width="40"
          height="40" />
      </a>
      <a href="https://www.python.org" target="_blank">
        <img
          src="https://devicons.github.io/devicon/devicon.git/icons/python/python-original.svg"
          alt="python"
          width="40"
          height="40" />
      </a>
      <a href="https://reactjs.org/" target="_blank">
        <img
          src="https://devicons.github.io/devicon/devicon.git/icons/react/react-original-wordmark.svg"
          alt="react"
          width="40"
          height="40" />
      </a>
      <a href="https://redis.io" target="_blank">
        <img
          src="https://devicons.github.io/devicon/devicon.git/icons/redis/redis-original-wordmark.svg"
          alt="redis"
          width="40"
          height="40" />
      </a>
      <a href="https://redux.js.org" target="_blank">
        <img
          src="https://devicons.github.io/devicon/devicon.git/icons/redux/redux-original.svg"
          alt="redux"
          width="40"
          height="40" />
      </a>
      <a href="https://www.rust-lang.org" target="_blank">
        <img
          src="https://devicons.github.io/devicon/devicon.git/icons/rust/rust-plain.svg"
          alt="rust"
          width="40"
          height="40" />
      </a>
      <a href="https://sass-lang.com" target="_blank">
        <img
          src="https://devicons.github.io/devicon/devicon.git/icons/sass/sass-original.svg"
          alt="sass"
          width="40"
          height="40" />
      </a>
      <a href="https://svelte.dev" target="_blank">
        <img
          src="https://upload.wikimedia.org/wikipedia/commons/1/1b/Svelte_Logo.svg"
          alt="svelte"
          width="40"
          height="40" />
      </a>
      <a href="https://vuejs.org/" target="_blank">
        <img
          src="https://devicons.github.io/devicon/devicon.git/icons/vuejs/vuejs-original-wordmark.svg"
          alt="vuejs"
          width="40"
          height="40" />
      </a>
      <a href="https://webpack.js.org" target="_blank">
        <img
          src="https://devicons.github.io/devicon/devicon.git/icons/webpack/webpack-original.svg"
          alt="webpack"
          width="40"
          height="40" />
      </a>
    </p>
  </div>

  <div class="codes">
    <h3>
      My favorite coding language right now is
      <a target="_blank" href="https://www.rust-lang.org/">Rust</a>,<br />
      I have been working on rust for a month now and it is very enjoyable.<br /><br />
      My first project in rust is,<br />
      <a target="_blank" href="https://github.com/willdoescode/nat">nat - the ls
        replacement you didn't know you needed</a>
      <br />
      <br />
      Some languages that I will learn in the future are
      <a target="_blank" href="https://golang.org/">Golang</a>
      and
      <a target="_blank" href="https://www.haskell.org/">Haskell</a>
    </h3>

    <div class="how">
      <h1 class="head how">How do I code?</h1>
      <h3>
        I code useing a in terminal text editor called
        <a target="_blank" href="https://www.vim.org/">Vim</a><br />
        with a config for it called
        <a target="_blank" href="https://spacevim.org/">SpaceVim</a>
      </h3>
    </div>
  </div>
</div>
