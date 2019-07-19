<style>
  section {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-evenly;
    height: 50vh;
    margin: 10vh 5vh 10vh 5vh;
  }

  div {
    text-align: center;
  }

  i {
    font-size: 1.5rem;
    margin: 0.5rem;
    color: rgb(18, 114, 93);
    transition: all 5ms ease-in-out;
  }

  i:hover {
    box-shadow: 2px 2px 6px rgb(21, 150, 122);
    border-radius: 13px;
  }

  img {
    border: 1.5px solid black;
    border-radius: 50%;
    height: 20rem;
    width: 17rem;
  }
</style>

<section id="about">
  <div>
    <img
      alt="me"
      src="https://images.unsplash.com/photo-1559581958-df379578606a?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=647&q=80" />
    <div>
      <a target="_blank" href="https://www.instagram.com/zdrifted/">
        <i class="fab fa-instagram" />
      </a>
      <a target="_blank" href="https://twitter.com/zdrifted">
        <i class="fab fa-twitter-square" />
      </a>
      <a target="_blank" href="https://www.linkedin.com/in/zdrifted/">
        <i class="fab fa-linkedin" />
      </a>
      <a target="_blank" href="https://www.github.com/zdrifted">
        <i class="fab fa-github-square" />
      </a>
    </div>
  </div>

  <div>
    <h1>Hi, I'm Luis Diaz</h1>
    <p>I work with Svelte.js, React.js, Node.js, Postgres and MongoDB</p>
    <p>This website is under construction</p>
  </div>
</section>
