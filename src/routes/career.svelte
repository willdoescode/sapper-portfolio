<style>
  @import url("https://fonts.googleapis.com/css2?family=Fira+Code&display=swap");
  @import url("https://fonts.googleapis.com/css2?family=Ubuntu&display=swap");

  * {
    padding: 0;
    margin: 0;
    color: whitesmoke;
  }

  .coding {
    display: flex;
    justify-content: center;
    margin-bottom: 20px;
  }

  .coding .code {
    width: 40vw;
  }

  .coding .desc {
    padding: 0px 0 0 50px;
  }

  .job-desc {
    margin-top: 15px;
  }

  .container {
    padding: 20px;
  }

  .kind {
    padding-top: 20px;
  }

  .top {
    margin-top: 20px;
  }

  .line {
    border-bottom: 1px solid whitesmoke;
    width: 69vw;
  }

  .containsline {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
  }

  .job {
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

  p {
    font-family: "Ubuntu";
  }

  header {
    display: flex;
    flex-direction: column;
    justify-content: center;
    text-align: center;
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
    margin-bottom: 50px;
  }

  .resources {
    display: flex;
    float: left;
    margin: 10px;
  }

  .rec {
    margin-top: 20px;
  }
</style>

<svelte:head>
  <title>Career - William lane</title>
</svelte:head>

<div class="container">
  <header class="head">
    <h1>Career</h1>
  </header>
  <div class="coding">
    <img class="code" src="images/code.png" alt="code" />
    <div class="desc">
      <h1 class="job">Coding</h1>
      <div class="job-desc">
        <p>
          Coding is something that I have been working on for a while.<br />
          I have been coding in Python for three years, Java for two years,<br />
          Javascript and webdev for a year, and I have just started to learn<br />
          Rust and golang.<br />
        </p>
      </div>
      <h1 class="job kind">What kind of coding?</h1>
      <div class="job-desc">
        <p>
          Lately I have been enjoying systems programming with Rust<br />
          but I also enjoy Web Development which is why I think it would<br />
          be cool to work at Mozilla. Currently at Mozilla they are building<br />
          a rendering engine like chromium written in Rust, I think this could<br />
          be a great opportunity to have a mix of systems and web programming<br />
          in a job.
        </p>
      </div>
    </div>
  </div>
  <div class="containsline">
    <div class="line" />
  </div>
  <div class="coding top">
    <img
      src="https://entrackr.com/wp-content/uploads/2018/12/startup-1-1200x600.jpg"
      alt="code"
      class="code" />
    <div class="desc">
      <h1 class="job">Other coding options</h1>
      <div class="job-desc">
        <p>
          I also like other coding than systems coding, I very much enjoy
          wesite&nbsp;&nbsp;&nbsp;<br />
          design. In a startup company I could do both website design and<br />
          server architecture with more strongly typed languages.
        </p>
        <h1 class="job rec">Recources</h1>
        <div class="resources">
          <ul>
            <li>
              <a
                target="_blank"
                href="https://www.github.com/willdoescode">willdoescode github</a>
            </li>
            <li>
              <a target="_blank" href="https://www.will.tools">will.tools</a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</div>
