<template>
	<div id="app">
		<header-nav></header-nav>
		<!-- <store-list></store-list> -->
		<body-content></body-content>
		<contact-list></contact-list>
		<footer-content></footer-content>
	</div>
</template>

<script>
import HeaderNav from './components/HeaderNav';
import Footer from './components/Footer';
import SignIn from './components/SignIn';
import SignUp from './components/SignUp';
import BodyContent from './components/BodyContent';
import Contact from './components/Contact';
import Store from './components/Store';

export default {
	components: {
		'header-nav': HeaderNav,
		'footer-content': Footer,
		'sign-in': SignIn,
		'sign-up': SignUp,
		'body-content': BodyContent,
		'store-list': Store,
		'contact-list': Contact,
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
