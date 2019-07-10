<style>
  h1 {
    text-align: center;
  }
  section {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-evenly;
    height: 85vh;
    margin: 10vh 5vh 0vh 5vh;
  }

  div {
    margin: 5px;
    padding: 1rem;
    text-align: center;
    background-color: black;
    border-radius: 10rem;
    height: 3rem;
    max-width: 10rem;
  }

  i {
    font-size: 3rem;
  }

  img {
    height: 3rem;
    width: 3rem;
  }

  @media only screen and (min-width: 876px) {
    section {
      height: 45vh;
    }
  }

  @media only screen and (max-width: 721px) {
    /* section {
      padding-top: 15rem;
    } */
  }
</style>

<section id="services">
  <div>
    <i class="devicon-html5-plain-wordmark" />
    <i class="devicon-css3-plain-wordmark colored" />
    <p>Fast and responsive websites</p>
  </div>
  <div>
    <i class="devicon-react-original-wordmark" />
    <img alt="svelte-logo" src="favicon.png" />
    <p>Dynamic web apps</p>
  </div>
  <div>
    <i class="devicon-nodejs-plain-wordmark" />
    <i class="devicon-mongodb-plain" />
    <p>Use an API or build one</p>
  </div>

  <div>
    <i class="devicon-heroku-original-wordmark" />
    <p>Host your web app on Heroku or Netlify</p>
  </div>
</section>
