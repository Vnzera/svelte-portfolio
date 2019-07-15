<style>
  .form {
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    background: #076cb7;
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
    background-color: #025aa5;
    border-color: #01549b;
    color: white;
    height: 2.5rem;
    width: 4.75rem;
    margin: 0 auto;
  }
</style>

<form netlify name="contact" id="contact" class="form">

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
