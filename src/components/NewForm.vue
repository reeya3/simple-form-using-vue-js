<template>
  <div id="new-Form" >
    <h2>THIS IS A FORM</h2>
    <form>
  
      <label>Password</label>
       <input type="password" name="Password"  v-model.lazy="forms.password" value="Password" required />

       


         

    </form>


   
  </div>
</template>

<script >  
export default {
   data(){
    return{
      forms: {

      
       password: "",
      
}     


    }

}
  
}

</script>

<style>

</style>
