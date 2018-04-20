<template>
  <div id="app">
    <region-buttons/>
    <country-list/>
  </div>
</template>

<script>
import RegionButtons from './components/RegionButtons'
import CountryList from './components/CountryList'

export default {
  name: 'app',
  components : {
    RegionButtons,
    CountryList
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

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
