<style>
  section {
    display: flex;
    flex-wrap: wrap;
    padding: 5rem;
    justify-content: space-evenly;
  }

  div {
    margin: 1rem;
    padding: 1rem;
    height: 15rem;
    width: 15rem;
    color: white;
    text-align: center;
    min-width: 15rem;
    min-height: 15rem;
    box-shadow: 2px 2px 6px rgb(0, 0, 0);
    border-radius: 1rem;
    border: solid 0.01px #3e4f85;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
  }

  div a {
    background-color: #1e2122;
    color: #1196ff;
    text-decoration: none;
    width: 5rem;
    margin: 0 auto;
    box-shadow: 2px 2px 6px #003864;
    border-radius: 5px;
    border: solid 0.01px #3e4f85;
    padding: 0.3rem;
    cursor: pointer;
  }

  div a:hover {
    background-color: white;
  }

  .primary {
    background-color: black;
  }

  .alternate {
    background-color: #1e2122;
  }
</style>

<section id="projects">

  <div class="primary">
    <h1>Blog Website</h1>
    <p>Made with GatsbyJS</p>
    <a target="_blank" href="https://beginnerbase.com">Link</a>
  </div>

  <div class="alternate">
    <h1>News Fetcher</h1>
    <p>Made with React, styled-components and a News API</p>
    <a target="_blank" href="https://fetch-news.netlify.com">Link</a>
  </div>

  <div class="primary">
    <h1>Simon Game</h1>
    <p>Made with vanilla JavaScript and plain CSS</p>
    <a
      target="_blank"
      href="https://codepen.io/zdrifted/pen/qXwyYQ?editors=0010">
      Codepen
    </a>
  </div>

  <div class="alternate">
    <h1>CSS Grid Portfolio</h1>
    <p>Made with CSS Grid and Firebase</p>
    <a target="_blank" href="https://zdrifted.github.io/grid-portfolio/ ">
      Github
    </a>
  </div>
</section>
