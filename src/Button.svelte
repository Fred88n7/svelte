<script>
  export let type = "default";
</script>

<button class={type}><slot /></button>

<style>
  button {
    border: 10px;
    border-radius: 8px;
    background-color: grey;
    color: white;
    padding: 15px;
    margin: 4px;
    cursor: pointer;
  }
  button:hover {
    background-color: black;
  }
  .primary {
    color: var(--primary-font-color);
    background-color: var(--primary-color);
  }
  .secondary {
    color: var(--primary-font-color);
    background-color: var(--secondary-color);
  }
  .accent {
    color: var(--primary-font-color);
    background-color: var(--accent-color);
  }
  .ghost {
    color: var(--ghost-font-color);
    background-color: var(--ghost-color);
  }
  .link {
    color: var(--link-color);
    background-color: var(--ghost-color);
  }

  .primary:hover {
    color: var(--primary-font-color);
    background-color: var(--secondary-color);
  }

  .secondary:hover {
    color: var(--primary-font-color);
    background-color: var(--ghost-color);
  }

  .accent:hover {
    color: var(--primary-font-color);
    background-color: var(--gjost-color);
  }

  .ghost:hover {
    color: var(--ghost-font-color);
    background-color: var(--accent-color);
  }

  .link:hover {
    color: var(--link-color);
    background-color: var(--primary-color);
  }
</style>
