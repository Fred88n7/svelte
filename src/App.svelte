<script>
  import Footer from "./Footer.svelte";
  import Badge from "./Badge.svelte";
  import Button from "./Button.svelte";
  import Card from "./Card.svelte";
</script>

<h2>Badge</h2>
<div class="badge_bar">
  <article>
    <h3>Default</h3>
    <Badge>Mit Badge</Badge>
    <div class="badge">
      <pre><code>{"<Badge>Mit Badge</Badge>"}</code></pre>
    </div>
  </article>
  <article>
    <h3>Primary</h3>
    <Badge type="primary">Mit Badge</Badge>
    <div class="badge">
      <pre><code>{"<Badge type=primary>Mit Badge</Badge>"}</code></pre>
    </div>
  </article>
  <article>
    <h3>Secondary</h3>
    <Badge type="secondary">Mit Badge</Badge>
    <div class="badge">
      <pre><code>{"<Badge type=secondary>Mit Badge</Badge>"}</code></pre>
    </div>
  </article>
  <article>
    <h3>Accent</h3>
    <Badge type="accent">Mit Badge</Badge>
    <div class="badge">
      <pre><code>{"<Badge type=accent>Mit Badge</Badge>"}</code></pre>
    </div>
  </article>
  <article>
    <h3>Ghost</h3>
    <Badge type="ghost">Mit Badge</Badge>
    <div class="badge">
      <pre><code>{"<Badge type=ghost>Mit Badge</Badge>"}</code></pre>
    </div>
  </article>
</div>

<h2>Buttons</h2>
<div class="button_bar">
  <article>
    <h3>Default</h3>
    <Button>Min knap</Button>
    <div class="button">
      <pre><code>{"<Button>Min knap</Button>"}</code></pre>
    </div>
  </article>
  <article>
    <h3>Primary</h3>
    <Button type="primary">Min knap</Button>
    <div class="button">
      <pre><code>{"<Button type=primary>Min knap</Button>"}</code></pre>
    </div>
  </article>
  <article>
    <h3>Secondary</h3>
    <Button type="secondary">Min knap</Button>
    <div class="button">
      <pre><code>{"<Button type=secondary>Min knap</Button>"}</code></pre>
    </div>
  </article>
  <article>
    <h3>Accent</h3>
    <Button type="accent">Min knap</Button>
    <div class="button">
      <pre><code>{"<Button type=accent>Min knap</Button>"}</code></pre>
    </div>
  </article>
  <article>
    <h3>Ghost</h3>
    <Button type="ghost">Min knap</Button>
    <div class="button">
      <pre><code>{"<Button type=ghost>Min knap</Button>"}</code></pre>
    </div>
  </article>
  <article>
    <h3>Link</h3>
    <Button type="link">Min knap</Button>
    <div class="button">
      <pre><code>{"<Button type=link>Min knap</Button>"}</code></pre>
    </div>
  </article>
</div>

<div class="card_container" />

<h2>Footer</h2>
<Footer />

<style>
  .badge_bar {
    display: flex;
    flex-direction: row;
    flex-flow: wrap;
    justify-content: space-evenly;
    padding-top: 50px;
  }

  .button_bar {
    display: flex;
    flex-direction: row;
    flex-flow: wrap;
    justify-content: space-evenly;
    padding-top: 50px;
  }

  .badge {
    border-radius: 20px;
    padding-left: 20px;
    padding-right: 20px;
    color: var(--primary-font-color);
    background-color: var(--background-color);
  }

  .button {
    color: var(--primary-font-color);
    background-color: var(--background-color);
    border-radius: 20px;
    padding-left: 20px;
    padding-right: 20px;
  }
</style>
