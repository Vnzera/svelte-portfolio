<style>
  button {
    font: inherit;
    padding: 0.15rem 0.5rem;
    background: rgb(18, 114, 93);
    border: 1px solid rgb(18, 114, 93);
    color: white;
    cursor: pointer;
    transition: all 0.15s ease 0s;
  }

  button:hover,
  button:active {
    box-shadow: 1px 1px 6px rgb(21, 150, 122);
  }
</style>

<!-- slots are placeholders for content/markup -->
<button on:click>
  <slot />
</button>
