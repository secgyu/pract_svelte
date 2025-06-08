<script>
  let language = {
    name : 'Svelte',
    release: 2016,
    src: 'https://svelte.dev/favicon.png'
  }
  let {name, release, src} = language
</script>

<h3>이름 : {name}</h3>
<h3>배포 연도 : {release}</h3>
<img src={src} alt="svelte logo" width="100">