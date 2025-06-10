<script>
  import Child from "./Child.svelte";

  let age01 = 20
  let age02 = 21

  const ageUp = () => {
    age01++
    age02++
  }

  const ageMinus = () => {
    age01--
    age02--
  }
</script>

<Child name="김철수" age={age01} hobby={'축구'}/>
<Child name="이영희" age={age02} hobby={'넷플릭스 보기'}/>

<button on:click={ageMinus}>나이 감소</button>
<button on:click={ageUp}>나이 증가</button>
