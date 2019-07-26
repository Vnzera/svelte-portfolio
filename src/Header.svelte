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
    padding: 0.5rem auto 1rem auto;
    margin: 1rem auto 5rem 1rem;
    position: fixed;
    width: 92%;
    z-index: 2s;
    background: rgba(240, 240, 240 0.7);
    box-shadow: 2px 2px 6px #003864;
    border-radius: 13px;
    padding: 0.5rem;
    background-color: #1e2122;
  }

  .navbar {
    display: flex;
    justify-content: flex-end;
    align-items: center;
    margin-right: 5rem;
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
  }

  a:hover,
  a:active {
    box-shadow: 2px 2px 6px #003864;
    border-radius: 5px;
    color: #1196ff;
    background-color: white;
  }

  /* icon styles */

  i {
    font-size: 1.5rem;
    cursor: pointer;
  }

  .fa-code {
    margin-right: auto;
    margin-left: 1rem;
  }

  /* overlay for modal on mobile */
  #modal {
    height: 100%;
    width: 0; /*manipulate this in the script*/
    position: fixed;
    z-index: 1;
    left: 0;
    top: 0;
    background-color: white;
    overflow-x: hidden;
    transition: all 0.5s ease 0s;
  }

  /* styles for mobile nav */

  #open {
    box-shadow: 2px 2px 6px #003864;
    border-radius: 5px;
    margin: 0.3rem;
    padding: 0.3rem;
    cursor: pointer;
  }

  #open:hover {
    background-color: #003864;
    color: white;
  }

  #mobile {
    display: flex;
    height: 100%;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }

  #mobile a {
    padding: 0.4rem;
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
    border-radius: 40px;
    background-color: white;
    color: #003864;
  }

  #close:hover {
    box-shadow: 2px 2px 6px #003864;
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
        <li>
          <i class="fas fa-arrow-alt-circle-left" />
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
