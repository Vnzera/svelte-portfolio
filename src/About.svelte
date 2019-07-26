<style>
  section {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-evenly;
    height: 30rem;
    margin: 0 auto 1rem auto;
    padding: 15rem 5rem 10rem 5rem;
  }

  div {
    text-align: center;
    padding: 1rem;
  }

  .bio {
    text-shadow: 0.2px 0.2px 0.2px grey;
    padding: 0rem 1rem 1rem 1rem;
    margin: 5rem;
    box-shadow: 2px 2px 6px rgb(6, 6, 6);
    border-radius: 13px;
    width: 18rem;
    height: 10rem;
  }

  i {
    font-size: 1.5rem;
    margin: 0.5rem;
    padding: 0.3rem;
    color: #003864;
    transition: all 5ms ease-in-out;
  }

  i:hover {
    box-shadow: 2px 2px 6px #003864;
    border-radius: 13px;
  }

  img {
    border: 1.5px solid black;
    height: 20rem;
    width: 17rem;
    box-shadow: 2px 2px 6px #003864;
    border-radius: 13px;
    padding: 0.2rem;
  }
</style>

<section id="about">
  <div>
    <img
      alt="me"
      src="https://images.unsplash.com/photo-1559581958-df379578606a?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=647&q=80" />
    <div class="icons">
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

  <div class="bio">
    <h1>Hi, I'm Luis</h1>
    <p>
      My favorite tech includes Svelte.js, React.js, Node.js and Postgres
      <br />
    </p>
  </div>
</section>
