<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>쇼핑센터 바로가기</h2>
    <ul>
      <li>
        <a
          href="https://vuejs.org"
          target="_blank">
          11st.co.kr
        </a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'MyReal',
  data () {
    return {
      msg: '이것은 나의 진짜 모듈'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
