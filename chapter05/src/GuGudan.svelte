<script>
  let dan = 2
  let numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9]

  $ : if(dan > 9) {
    alert('구구단은 9단을 초과할 수 없습니다.')
    dan = 9
  }

  $ : if(dan < 2) {
    alert('구구단은 2단보다 작을 수 없습니다.')
    dan = 2
  }

  const increase = () => dan++
  const decrease = () => dan--
</script>

<h1>구구단 출력</h1>
<span><strong>{dan} 단</strong></span>
<button on:click={decrease}>-</button>
<button on:click={increase}>+</button>

{#each numbers as number}
  <p>{dan} * {number} = {dan * number}</p>
{/each}