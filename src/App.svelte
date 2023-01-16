<script>
  let text_value = '';

  $: fucks = (text_value.match(/fuck/g) || []).length;
</script>

<main>
  <h1>Hello from Svelte</h1>
  <input bind:value={text_value} />
  <p>{fucks}</p>
  <p>What a beautiful framework</p>
</main>
