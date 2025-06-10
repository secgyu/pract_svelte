<script>
  import Child from "./Child.svelte";

  const allData = {
    name: '김철수',
    age: 20,
    hobby:'축구'
  }
  const allData2 = {
    name: '이영희',
    age: 21,
    hobby: '넷플릭스 보기'
  }
</script>

<Child {...allData} />
<Child {...allData2} />