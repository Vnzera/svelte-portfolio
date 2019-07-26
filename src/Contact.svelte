<style>
  section {
    margin: 1rem;
    padding-bottom: 1rem;
  }

  @media only screen and (max-width: 800px) {
    section {
      margin: 0;
      padding-bottom: 0;
    }
  }

  .form {
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    background: #1e2122;
    color: white;
    padding: 0.625rem;
    margin: 5rem auto 10rem auto;
    border-radius: 1.6875rem;
    border: 2px solid #383232;
    text-align: center;
    width: 17rem;
    height: 25rem;
  }

  input,
  textarea {
    width: 100%;
    padding: 9px 0;
  }

  label {
    color: #1196ff;
    padding: 0.3rem;
  }

  #submit {
    background-color: #1e2122;
    border-color: #01549b;
    color: #1196ff;
    height: 2.5rem;
    width: 4.75rem;
    margin: 0 auto;
    padding: 0.5rem;
    box-shadow: 2px 2px 6px #003864;
    border-radius: 5px;
    border: solid 0.01px #3e4f85;
  }

  #submit:hover {
    background-color: black;
  }
</style>

<section id="contact">

  <form data-netlify="true" name="contact" method="POST" class="form">

    <div>
      <label for="email">Email address</label>
      <input
        type="email"
        name="email"
        aria-describedby="emailHelp"
        placeholder="Enter email" />
      <small>We'll never share your email with anyone else.</small>
    </div>

    <div>
      <label for="subject">Subject</label>
      <input type="text" name="subject" placeholder="Enter subject" />
    </div>

    <div>
      <label for="message">Message</label>
      <textarea name="message" rows="3" placeholder="Enter your message here" />
    </div>

    <button type="submit" id="submit">Submit</button>

  </form>

</section>
