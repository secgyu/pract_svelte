<script>
  let langs = [
    {
      name : 'Svelte',
      release: 2016,
      src: 'https://svelte.dev/favicon.png'
    },
    {
      name : 'React',
      release: 2013,
      src: 'https://react.dev/favicon.ico'
    },
    {
      name : 'Vue',
      release: 2014,
      src: 'https://vuejs.org/images/logo.png'
    }
  ]
</script>

{#each langs as lang }
  <h3>이름 : {lang.name}</h3>
  <h3>배포 년도 : {lang.release}</h3>
  <img src={lang.src} alt="logo" height="50">
  <hr>
{/each}