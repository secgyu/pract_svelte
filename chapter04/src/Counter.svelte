<script>
  let num = 0
  let count = 0

  const plus = () => {
    num++
    count++
  }

  const minus = () => {
    num--
  }
</script>

<h1>클릭 횟수 : {count}</h1>
<hr>
<p>{num}</p>
<button on:click={plus}>plus</button>
<button on:click={minus}>minus</button>

