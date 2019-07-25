<style>
  section {
    display: flex;
    flex-wrap: wrap;
    margin: 1rem auto 0.5rem auto;
    padding: 10rem;
    justify-content: space-evenly;
  }

  div {
    margin: 0.5rem;
    padding: 0.5rem;
    height: 15rem;
    width: 15rem;
    color: white;
    text-align: center;
    min-width: 15rem;
    min-height: 15rem;
    box-shadow: 2px 2px 6px rgb(0, 0, 0);
    border-radius: 1rem;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
  }

  div a {
    color: rgb(231, 221, 221);
    text-decoration: none;
    box-shadow: 2px 2px 6px rgb(0, 0, 0);
    border-radius: 0.5rem;
    padding: 0.5rem;
    width: 5rem;
    margin: 0 auto;
  }

  .primary {
    background-color: #062f4f;
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
