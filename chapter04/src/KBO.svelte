<script>
  let teams = [
    {
      name : 'KIA',
      founded: 2001,
      location: '광주'
    },
    {
      name : '삼성',
      founded: 1982,
      location: '대구'
    },
    {
      name : 'LG',
      founded: 1990,
      location: '서울'
    },
      {
        name : '두산',
        founded: 1982,
        location: '서울'
      },
      {
      name : 'KT',
      founded: 2013,
      location: '수원'
    },
    {
      name : 'SSG',
      founded: 2021,
      location: '인천'
    },
    {
      name : '롯데',
      founded: 1982,
      location: '부산'
    },
    {
      name : '한화',
      founded: 1986,
      location: '대전'
    },
    {
      name : 'NC',
      founded: 2011,
      location: '창원'
    },
    {
      name : '키움',
      founded: 2008,
      location: '서울'
    },
  ]
</script>
<h3>KBO 팀 정보</h3>
{#each teams as team}
  <h3>팀 이름 : {team.name}</h3>
  <h3>설립 년도 : {team.founded}</h3>
  <h3>연고지 : {team.location}</h3>
  <hr>
{/each}