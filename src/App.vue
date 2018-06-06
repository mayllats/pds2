<template>
  <div id="app">
    <cc-nav></cc-nav>
    <cc-page-title></cc-page-title>
    <cc-tab></cc-tab>
    <cc-btn></cc-btn>
    <cc-form-cliente></cc-form-cliente>
    <cc-client-list></cc-client-list>

  </div>
</template>

<script>
import CcNav from './components/CcNav'
import CcTab from './components/CcTab'
import CcFormCliente from './components/CcFormCliente'
import CcPageTitle from './components/CcPageTitle'
import CcClientList from './components/CcClientList'
import CcBtn from './components/CcBtn'

export default {
  name: 'ecommerceComponent',
  components:{
    CcNav, CcTab,CcBtn, CcFormCliente, CcPageTitle, CcClientList
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
