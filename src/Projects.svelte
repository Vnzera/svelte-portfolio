<style>
  section {
    display: flex;
    flex-wrap: wrap;
    margin-top: 10px;
    justify-content: space-evenly;
  }

  div {
    margin: 5px;
    padding: 1rem;
    height: 20rem;
    width: 20rem;
    color: white;
    text-align: center;
  }

  div a {
    color: rgb(231, 221, 221);
  }

  .red {
    background-color: #b82601;
  }

  .blue {
    background-color: #062f4f;
  }

  .yellow {
    background: #d9b310;
  }

  .purple {
    background: #813772;
  }
</style>

<section id="projects">
  <div class="blue">
    <h1>Online Jewelry Store</h1>
    <p>Made with Svelte.js, Node and MongoDB</p>
    <a href="#">Live Link</a>
  </div>

  <div class="red">
    <h1>Random Definition Generator</h1>
    <p>Made with React, MaterialUI and the Wordnik API</p>
    <a href="https://random-word-definition.herokuapp.com/">Heroku Link</a>
  </div>

  <div class="yellow">
    <h1>Simon Game</h1>
    <p>Made with vanilla JavaScript and plain CSS</p>
    <a href="https://codepen.io/zdrifted/pen/qXwyYQ?editors=0010">
      Codepen Link
    </a>
  </div>

  <div class="purple">
    <h1>CSS Grid Portfolio</h1>
    <p>Made with CSS Grid and Firebase</p>
    <a href="https://zdrifted.github.io/grid-portfolio/ ">Github Link</a>
  </div>
</section>
