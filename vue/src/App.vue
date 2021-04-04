<template>
  <div>
    <dashboard-wrapper :api="api" :params="params" id="inst1" style="height:85%;width:100%;position:absolute" editmode="true" :dashboard="dashboard" :token="token" :platformbase="platformbase" i18n="false">
    </dashboard-wrapper>
  </div>
</template>

<script>

import dashboardWrapper from './components/VueWrapperComponent.vue';

export default {
  components: {
    dashboardWrapper
  },
  data: function(){
    return {
      dashboard: "15edf58b-a6e2-448c-b170-eda467e319df",
      token: "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJwcmluY2lwYWwiOiJwbW91cmEiLCJjbGllbnRJZCI6Im9uZXNhaXRwbGF0Zm9ybSIsInVzZXJfbmFtZSI6InBtb3VyYSIsInNjb3BlIjpbIm9wZW5pZCJdLCJuYW1lIjoicG1vdXJhIiwiZXhwIjoxNjE3NTg4NTkxLCJncmFudFR5cGUiOiJwYXNzd29yZCIsInBhcmFtZXRlcnMiOnsidmVydGljYWwiOm51bGwsImdyYW50X3R5cGUiOiJwYXNzd29yZCIsInVzZXJuYW1lIjoicG1vdXJhIn0sImF1dGhvcml0aWVzIjpbIlJPTEVfREFUQVNDSUVOVElTVCJdLCJqdGkiOiI0NmRjYzMwMy00YzU3LTRjYjgtODljOC0wNjcwZGUzZmM0YzYiLCJjbGllbnRfaWQiOiJvbmVzYWl0cGxhdGZvcm0ifQ.wrvlMWip7voi9JjzXpFB0I8bPQ3ZKR1tZ4Hpp5HcOfw",
      platformbase: "https://lab.onesaitplatform.com",
      params: {},
      api: {}
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
