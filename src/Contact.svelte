<style>
  #form {
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    background: #076cb7;
    color: white;
    padding: 0.625rem;
    margin: 5rem auto;
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

  /* .form-group {

  }

  .form-control {

  } */
</style>

<form id="form" method="post" action="">

  <div class="form-group">
    <label for="email">Email address</label>
    <input
      type="email"
      class="form-control"
      id="email"
      name="email"
      aria-describedby="emailHelp"
      placeholder="Enter email" />
    <small id="emailHelp" class="form-text text-muted">
      We'll never share your email with anyone else.
    </small>
  </div>

  <div class="form-group">
    <label for="subject">Subject</label>
    <input
      type="text"
      class="form-control"
      id="subject"
      name="subject"
      placeholder="Enter subject" />
  </div>

  <div class="form-group">
    <label for="message">Message</label>
    <textarea
      class="form-control"
      id="message"
      name="message"
      rows="3"
      placeholder="Enter your message here" />
  </div>

  <button type="submit" id="submit" name="submit">Submit</button>

</form>
