<template>
	<div id="app">
		<body-content></body-content>
	</div>
</template>

<script>
import HeaderNav from './components/HeaderNav';
import SignIn from './components/SignIn';
import SignUp from './components/SignUp';
import BodyContent from './components/BodyContent';
import Store from './components/Store';

export default {
	components: {
		'header-nav': HeaderNav,
		'sign-in': SignIn,
		'sign-up': SignUp,
		'body-content': BodyContent,
		'store-list': Store,
	},
	name: 'app',
	data() {
		return {
			msg: 'Welcome to Your Vue.js App',
		};
	},
};
</script>

<style lang="scss">
#app {
	font-family: 'Avenir', Helvetica, Arial, sans-serif;
}
</style>
