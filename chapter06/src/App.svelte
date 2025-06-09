<script>
  import GoGoogle from "./GoGoogle.svelte";

  const handleClick1 = () => alert('한번만 제공합니다.')
  const handleClick2 = () => alert('클릭이 계속 실행됩니다.')
</script>

<button on:click|once={handleClick1}>1번 버튼</button>
<button on:click={handleClick2}>2번 버튼</button>

<GoGoogle />