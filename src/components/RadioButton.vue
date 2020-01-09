<template>
  <div id="radio-button" >
  
        <label>male</label>
        <input type="checkBox" value="" v-model="forms.categories"/>

        <label>female</label>
        <input type="checkBox" value="forms.categories"/>

    

   
  </div>
</template>

<script>


export default {
   data(){
    return{
      forms: {
    
       categories: [male,female]
}   

}
}
}
</script>