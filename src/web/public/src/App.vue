<template>
<div id="app">
  <!-- <img src="./assets/logo.png"> -->
  <!--hello></hello-->
  <search>
    <template slot="header">
      <h1>zjucx</h1>
    </template>
    <template slot="content">
      <searchInput>
      </searchInput>
    </template>
  </search>
</div>
</template>

<script>
import Hello from './components/Hello'
import Search from './components/Search'
import SearchInput from './components/SearchInput'

export default {
  name: 'app',
  components: {
    Hello,
    Search,
    SearchInput
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  /*color: #2c3e50;*/
  background: #DEDFE0;
  margin-top: 60px;
}
#app h1 {
	/*position: absolute;*/
	font-size: 100px;
	font-weight: 100;
	text-align: center;
  margin-top: 0;
  background:transparent;
  background-color:rgba(255,255,255,0)
}
</style>
