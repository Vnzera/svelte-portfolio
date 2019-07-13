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
    display: flex;
    justify-content: flex-end;
    align-items: center;
    padding: 30px 10%;
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
    padding: 0px 10px;
  }

  a,
  i {
    text-decoration: none;
    color: rgb(18, 114, 93);
  }

  a:hover,
  a:active {
    box-shadow: 2px 2px 6px rgb(21, 150, 122);
    border-radius: 5px;
  }

  /* icon styles */

  i {
    font-size: 1.5rem;
    cursor: pointer;
  }

  .fa-code {
    margin-right: auto;
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
    box-shadow: 2px 2px 6px rgb(21, 150, 122);
    border-radius: 5px;
    margin: 5px;
    padding: 1.5px;
    cursor: pointer;
  }
  #mobile {
    display: flex;
    height: 100%;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }

  #mobile a {
    padding: 15px;
    font-size: 36px;
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
    color: rgb(18, 114, 93);
  }

  #close:hover {
    box-shadow: 2px 2px 6px rgb(21, 150, 122);
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
  <i class="fas fa-code" />
  <nav>
    <a href="#menu" id="open" on:click={openNav}>Menu</a>
    <ul>
      <li>
        <a href="#header">Home</a>
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

</header>

<!-- clicking a mobile link should close out the modal also.  -->

<div id="modal">
  <button id="close" on:click={closeNav}>X</button>
  <div id="mobile">
    <a href="#header" on:click={closeNav}>Home</a>
    <a href="#projects" on:click={closeNav}>Projects</a>
    <a href="#contact" on:click={closeNav}>Contact</a>
  </div>
</div>
