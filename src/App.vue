<template>
  <div id="app">
    <cc-nav></cc-nav>
    <cc-page-title></cc-page-title>
    <cc-tab></cc-tab>
    <cc-form-cliente></cc-form-cliente>

  </div>
</template>

<script>
import CcNav from './components/CcNav'
import CcTab from './components/CcTab'
import CcFormCliente from './components/CcFormCliente'
import CcPageTitle from './components/CcPageTitle'

export default {
  name: 'ecommerceComponent',
  components:{
    CcNav, CcTab, CcFormCliente, CcPageTitle
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 0px;
}
</style>
