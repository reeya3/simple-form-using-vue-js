<template>
  <div >
     <Email/>
    <NewForm />
   
      <Preview/>
        <button/>
       
   
  </div>
</template>

<script>
import Email from  './components/Email.vue'
import NewForm from './components/NewForm.vue'

import RadioButton from  './components/RadioButton.vue'
import Preview from  './components/Preview.vue'




export default {
components:{
  NewForm,
  Email,
 Preview,
 TxtArea
}
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

