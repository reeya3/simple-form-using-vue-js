<template>
 

    <div id="button">
  <button v-on:click="Say('ease wai')">log in</button>
  

   
  </div>
</template>

<script>


export default {
	method:{
	say(msg){

		alert(msg);
	}

} 
}
</script>