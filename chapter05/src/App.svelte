<script>
  import GuGudan from "./GuGudan.svelte";
  import Reactivity from "./Reactivity.svelte";
  import ReactivityIf from "./ReactivityIf.svelte";

  let count = 1
  const handleClick = () => count++
</script>

<button on:click={handleClick}>
  클릭 수 : {count} {count === 1 ? 'time' : 'times'}
</button>
<br>
<Reactivity />
<ReactivityIf />
<GuGudan />