<template>
	<div>
  	<label>Email:</label>

  	<input type="text" name="Email" v-model.lazy="forms.email" required />
  	
  </div>
</template>

<script>


export default {
	data(){
		return {
			forms: {
				email:"",
			}
		}
	}
}
</script>
