<template>
	<div class="Login">
		<h2>Bienvenido a Login</h2>
		<router-link to="/" exact>Home</router-link>
		<form @submit.prevent="updateStudent">
			<input  type="email" name="email" v-model  placeholder="email"  >
			<input type="password" name="password"  placeholder="******" >
			<input type="submit" name="" value="enviar">
		</form>
	</div>
</template>

<script>
export default {

  name: 'Login',
  data () {
    return {
      email: '',
      password: ''
    }
  },
  methods: {
    login (e) {
      
    }
  }
}
</script>

<style lang="css" scoped>
</style>