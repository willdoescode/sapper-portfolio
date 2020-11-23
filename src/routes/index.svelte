<script>
  import { dataset_dev } from "svelte/internal";
  const fetchImage = (async () => {
    const response = await fetch(
      "https://api.github.com/repos/willdoescode/nat?page=$i&per_page=100"
    );
    return await response.json();
  })();
</script>

<style>
  @import url("https://fonts.googleapis.com/css2?family=Lora:wght@700&display=swap");
  * {
    margin: 0;
    padding: 0;
    background: none;
    color: whitesmoke;
  }
  h1,
  p {
    text-align: center;
    margin: 0 auto;
  }

  h1 {
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
    transition: 0.3s;
  }

  @keyframes shake {
    0% {
    }
    30% {
      transform: rotate(-10deg);
    }
    70% {
      transform: rotate(10deg);
    }
    100% {
      transform: rotate(0deg);
    }
  }

  .main {
    margin-top: 30px;
    text-align: center;
  }

  @media (min-width: 480px) {
    h1 {
      font-size: 4em;
    }
  }
  .container {
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 20px 0 0 0;
  }

  .border-bottom {
    border-bottom: 2px solid rgba(255, 255, 255, 0.5);
    width: 480px;
  }

  .current {
    margin: 10px 0 20px 0;
    background-image: linear-gradient(45deg, #f3ec78, #af4261);
    background-size: 100%;
    -webkit-background-clip: text;
    -moz-background-clip: text;
    -webkit-text-fill-color: transparent;
    -moz-text-fill-color: transparent;
    font-weight: bold;
  }

  .current-list a {
    text-decoration: none;
    transition: 0.5s;
    font-weight: bold;
    color: rgb(255, 186, 102);
  }

  .current-list a:hover {
    text-decoration: underline;
    text-decoration-color: tomato;
  }
</style>

<svelte:head>
  <title>William lane</title>
</svelte:head>

<div class="main">
  <h1>William Lane</h1>
  <p>{new Date().getFullYear() - 2006} year old coder from Camas, Washington</p>
  <div class="container">
    <div class="border-bottom" />
  </div>

  <div class="projects">
    <h3 class="current">Current projects</h3>
    <ul class="current-list">
      <li>
        <a target="_blank" href="https://github.com/willdoescode/nat">
          {#await fetchImage}
            0
          {:then data}
            {#if data.description != undefined}
              {data.description}
            {:else}Not availible{/if}
          {/await}
        </a>
      </li>
      <li>
        <a
          target="_blank"
          href="https://github.com/willdoescode/rust-algorithms">
          rust algorithm practice
        </a>
      </li>
    </ul>

    <h3 class="current">Accomplishments</h3>
    <ul class="current-list">
      <li>
        A large German tech blog wrote about my project in an
        <a
          target="_blank"
          href="https://www.heise.de/news/In-Rust-geschrieben-und-uebersichtlicher-nat-will-ls-ersetzen-4937429.html">article</a>
      </li>
      <li>
        {#await fetchImage}
          0
        {:then data}
          ⭐️
          {data.stargazers_count}
          stars and 🍴
          {data.forks_count}
          forks on the
        {:catch error}
          Error fetching stars
        {/await}
        <a target="blank" href="https://github.com/willdoescode/nat">nat github
          repo</a>
      </li>
    </ul>
  </div>

  <div class="container">
    <div class="border-bottom" />
  </div>

  <a href="https://www.notion.so/Website-design-learning-log-2a886f26aa534c32a4b7a100a5cb85f3" target="_blank">Learning log</a>
</div>
