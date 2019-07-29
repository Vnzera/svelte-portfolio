<style>
  section {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-evenly;
    height: 30rem;
    margin: 0 auto 1rem auto;
    padding: 8rem 5rem 16rem 5rem;
  }

  @media only screen and (min-width: 800px) {
    section {
      padding-top: 15rem;
    }
  }

  @media only screen and (min-width: 934px) {
    section {
      padding-bottom: 1rem;
    }
  }

  div {
    vertical-align: middle;
    text-align: center;
  }

  .bio {
    text-shadow: 0.2px 0.2px 0.2px grey;
    padding: 1rem;
    margin: 5rem;
    box-shadow: 2px 2px 6px rgb(6, 6, 6);
    border-radius: 13px;
    width: 18rem;
    height: 10rem;
    min-width: 15rem;
  }

  i {
    font-size: 1.7rem;
    margin: 0.5rem;
    padding: 0.3rem;
    color: #003864;
    transition: all 0.3s ease 0s;
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
    <p>My favorite tech includes Svelte.js, React.js, Node.js and Postgres</p>
  </div>
</section>
