<script lang="ts">
  import pawLogo from './assets/paw.svg'
  import Search from './lib/Search.svelte'
</script>

<main>
  <div>
    <a href="https://svelte.dev" target="_blank" rel="noreferrer">
      <img src={pawLogo} class="logo svelte" alt="Svelte Logo" />
    </a>
  </div>
  <h1>Searcher</h1>

  <div class="box1">Prova</div>
  <p>Aaaas</p>
  <div class="card">
    <Search />
  </div>

</main>

<style>
  .logo {
    height: 6em;
    padding: 1.5em;
    will-change: filter;
    transition: filter 300ms;
  }
  .logo:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
  }
  .logo.svelte:hover {
    filter: drop-shadow(0 0 2em #ff3e00aa);
  }
</style>
