<script>
  const handleClick =() => {
    let move = confirm('구글로 이동하시겠습니까?')
    move && location.assign('https://www.google.com')
  }
</script>

<h1>
  <a href="https://www.google.com" on:click|preventDefault={handleClick}>구글 바로가기</a>
</h1>