<script lang="ts">
  const autocomplete = () => {}
  //fase anche di autocomplete
  const submit = () => {}
</script>

<div class="bar">
  <input on:change={autocomplete} class="searchbar" type="text" title="Search">
  <a href="#"> <img class="voice" src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e8/Google_mic.svg/716px-Google_mic.svg.png" title="Search by Voice"></a>
</div>

<button on:click={submit} class="button" type="button">
	Cerca
</button>
