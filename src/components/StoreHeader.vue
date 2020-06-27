<template>
	<div>
		<header class="site-header clearfix">
			<div class="container">
				<div class="row">
					<div class="col-md-12 pull-all">
						<div class="main-navigation pull-right">
							<nav class="main-nav visible-md visible-lg">
								<ul class="sf-menu">
									<li class="active"><a href="index.html">Home</a></li>
									<li><a href="#">Add Item</a></li>
									<li><a href="contact.html">Cart</a></li>
									<h3>Jecko</h3>
								</ul>
							</nav>
						</div>
					</div>
				</div>
			</div>
		</header>
	</div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
body {
	background: white;
	font-size: 16px;
	font-family: 'PT Serif', Georgia, serif;
	font-weight: normal;
	font-style: normal;
	line-height: 28px;
	color: #777777;
	-webkit-font-smoothing: antialiased;
	-webkit-text-size-adjust: 100%;
}

.main-nav ul,
.main_menu,
.main_menu li ul {
	list-style: none;
	padding: 0;
	margin: 0;
}

.site-header {
	position: relative;
	width: 100%;
	background: #f9f9f9;
	z-index: 9999;
	padding: 10px 0;
	overflow: visible;
	transition: padding 0.3s ease-in-out;
	-moz-transition: padding 0.3s ease-in-out;
	-webkit-transition: padding 0.3s ease-in-out;
}

.main-nav ul li {
	float: right;
	display: block;
	margin-left: 20px;
	position: relative;
}
.main-nav ul li a {
	color: #31373a;
	font-size: 16px;
	font-weight: 700;
	text-transform: uppercase;
	font-family: 'Raleway', sans-serif;
	padding: 5px 15px;
	display: block;
	-webkit-border-radius: 3px;
	-moz-border-radius: 3px;
	-ms-border-radius: 3px;
	-o-border-radius: 3px;
	border-radius: 3px;
}
.main-nav ul li a:hover {
	background-color: #f1f4f5;
	text-decoration: none;
	color: #3978d6;
}
.main-nav ul li a i {
	margin-left: 7px;
}
.main-nav ul li.active a {
	text-decoration: none;
	color: #0e4ba7;
	background-color: #f1f4f5;
}

.main-nav ul li ul li a {
	background-color: transparent !important;
	color: #777777 !important;
	text-transform: capitalize;
	font-weight: 600;
}
</style>
