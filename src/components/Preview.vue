
<template>

<div id ="preview">
          <h3>Preview</h3>
          <p>Email: {{forms.email}}</p>
          <p>Password : {{forms.password}}</p>
          <p>TextArea: {{forms.txtarea}}</p>
          <p>Categories</p>
            <ul> 
                <li v-for="category in categories" :key="category"> {{category}}</li>


          </ul>

       </div>


   
 
</template>

<script>


export default {
 data(){
    return{
      forms: {
       email:"",
       password: "",
       txtarea:"",
       categories: [] 

}
  }
}
}
</script>


