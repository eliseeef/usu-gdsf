<template>
	<div>
		<!-- File uploads: FormData -->
		<form >
			<v-row align="center" justify="center">
				<v-col>
					<v-text-field
					outlined
					label="Username">
					</v-text-field>
					<v-text-field
					outlined
					label="Password">
					</v-text-field>
				<router-link :to="{name: 'newuser', params: {isAdmin: true}}">New user? Create an account here</router-link>
				<!-- <router-link :to="{ name: 'info', params: { id: '2' }}">To another game</router-link> -->
				<v-btn align="center" justify="center">
					Login
				</v-btn>
				</v-col>
			</v-row>
		</form>
	</div>
</template>

<script>
export default {
	name: 'AdminPage',

}
</script>