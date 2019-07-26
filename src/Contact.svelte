<style>
  section {
    margin: 1rem;
    padding-bottom: 1rem;
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

  #submit {
    background-color: #1e2122;
    border-color: #01549b;
    color: white;
    height: 2.5rem;
    width: 4.75rem;
    margin: 0 auto;
    box-shadow: 2px 2px 6px rgb(0, 0, 0);
    border-radius: 0.5rem;
    padding: 0.5rem;
  }

  #submit:hover {
    background-color: black;
  }
</style>

<section>

  <form netlify name="contact" method="POST" id="contact" class="form">

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
