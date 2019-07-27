<script>
  function openNav() {
    document.getElementById("modal").style.width = "100%";
  }

  function closeNav() {
    document.getElementById("modal").style.width = "0";
  }
</script>

<style>
  header {
    padding: 0rem 1rem;
    margin: 0;
    position: fixed;
    width: 100%;
    height: 4rem;
    z-index: 1;
    background: rgba(240, 240, 240 0.7);
    box-shadow: 2px 2px 6px #003864;
    background-color: #1e2122;
  }

  .navbar {
    display: flex;
    justify-content: flex-end;
    align-items: center;
    margin-right: 4rem;
  }

  ul {
    list-style: none;
  }

  li,
  a {
    transition: all 0.2s ease 0s;
  }

  li {
    display: inline-block;
  }

  a,
  i {
    text-decoration: none;
    color: #1196ff;
    padding: 0.3rem;
    box-shadow: 2px 2px 6px #003864;
    border-radius: 5px;
    border: solid 0.01px #3e4f85;
  }

  a:hover,
  a:active {
    box-shadow: 2px 2px 6px #003864;
    border-radius: 5px;
    background-color: white;
  }

  /* icon styles */

  i {
    font-size: 1.5rem;
    cursor: pointer;
  }

  .fa-code {
    margin: 1rem auto 1rem 0rem;
  }

  /* overlay for modal on mobile */
  #modal {
    height: 100%;
    width: 0; /*manipulate this in the script*/
    position: fixed;
    z-index: 1;
    left: 0;
    top: 0;
    background-color: #1e2122;
    overflow-x: hidden;
    transition: all 0.5s ease 0s;
  }

  /* styles for mobile nav */

  #open {
    box-shadow: 2px 2px 6px #003864;
    border-radius: 5px;
    border: solid 0.01px #3e4f85;
    padding: 0.3rem;
    margin: 0.5rem;
    cursor: pointer;
    background-color: #1e2122;
  }

  #open:hover {
    background-color: white;
  }

  #mobile {
    display: flex;
    height: 100%;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }

  #mobile a {
    padding: 0.8rem;
    margin: 1rem;
    font-size: 2.3rem;
    display: block;
    transition: all 0.3s ease 0s;
  }

  /* styles for close button */
  #close {
    position: absolute;
    top: 20px;
    right: 45px;
    font-size: 40px;
    border-radius: 10px;
    background-color: #1e2122;
    box-shadow: 2px 2px 6px #003864;
    color: #1196ff;
    border-color: #3e4f85;
    transition: all 0.3s ease 0s;
  }

  #close:hover {
    background-color: white;
  }

  /* media quieries */
  @media only screen and (min-width: 800px) {
    #open {
      display: none;
    }
  }

  @media only screen and (max-width: 800px) {
    ul {
      display: none;
    }
  }
</style>

<header id="header">
  <div class="navbar">
    <i class="fas fa-code" />
    <nav>
      <a href="#menu" id="open" on:click={openNav}>Menu</a>
      <ul>
        <li>
          <a href="#about">Home</a>
        </li>
        <li>
          <a href="#projects">Projects</a>
        </li>
        <li>
          <a href="#contact">Contact</a>
        </li>
      </ul>
    </nav>
  </div>

</header>

<!-- clicking a mobile link should close out the modal also.  -->

<div id="modal">
  <button id="close" on:click={closeNav}>X</button>
  <div id="mobile">
    <a href="#about" on:click={closeNav}>Home</a>
    <a href="#projects" on:click={closeNav}>Projects</a>
    <a href="#contact" on:click={closeNav}>Contact</a>
  </div>
</div>
