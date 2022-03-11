<script>
  export let type = "default";
</script>

<span class={type}>
  <slot />
</span>

<style>
  span {
    border: 2px;
    border-radius: 12px;
    background-color: grey;
    color: white;
    padding: 6px;
    margin: 4px;
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
  }
</style>
