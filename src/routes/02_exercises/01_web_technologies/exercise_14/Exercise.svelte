<script>
  let current = "";
</script>

<style>
  .different {background-color: steelblue}
  .same {background-color: rgb(97,135,52)}
</style>

<!-- We will cover buttons later on! -->
<button class="btn" class:different={current!="messi"} class:same={current=="messi"} on:click={() => (current = "messi")}>
  Messi
</button>

<button class="btn" class:different={current!="ronaldo"} class:same={current=="ronaldo"} on:click={() => (current = "ronaldo")}>
  Ronaldo
</button>

<button class="btn" class:different={current!="neymar"} class:same={current=="neymar"} on:click={() => (current = "neymar")}>
  Neymar
</button>
