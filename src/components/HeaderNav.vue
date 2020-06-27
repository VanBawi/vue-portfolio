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
									<li><a href="#">Portfolio</a></li>
									<li><a href="#">Blog</a></li>
									<li><a href="archives.html">Archives</a></li>
									<li><a href="contact.html">Contact</a></li>
									<h3>Jecko</h3>
								</ul>
							</nav>
						</div>
					</div>
				</div>
			</div>
		</header>

		<!-- /.site-header -->
		<section id="homeIntro" class="parallax first-widget">
			<div class="parallax-overlay">
				<div class="container home-intro-content">
					<div class="row">
						<div class="col-md-12">
							<h2>How coding has changed the world for the better</h2>
							<div class="parallax-text col-md-auto">
								<p class="text-post">
									Who says you can’t change the world? History has repeatedly shown that whatever
									isn’t possible today can be possible tomorrow.
								</p>
								<button class=" btn button btn-lg btn-outline-danger">Want's Next?</button>
							</div>
						</div>
					</div>
				</div>
			</div>
		</section>
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
.first-widget {
	position: relative;
	margin-top: 61px;
	height: 650px;
	margin-bottom: 4rem;
}

/*------------------------------------------------------
	HEADER STYLES
--------------------------------------------------------*/
.site-header {
	position: fixed;
	top: 0;
	left: 0;
	width: 100%;
	background: #f9f9f9;
	z-index: 9999;
	padding: 10px 0;
	margin-bottom: 30px;
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

#homeIntro {
	background-image: url('../assets/images/wallpaper1.jpg');
}

.button {
	justify-self: start;
}

.parallax {
	background-attachment: fixed;
	background-repeat: no-repeat;
	background-position: center center;
	background-size: cover;
	color: #fff;
	overflow: hidden;
}

.parallax-overlay {
	background-color: rgba(0, 0, 0, 0.3);
}
.parallax-text {
	width: 40%;
	display: grid;
	margin: 0 auto;
}

.text-post {
	background-color: lightgrey;
	margin: 0 auto;
	padding: 15px;
	opacity: 0.4;
	font-weight: 600;
	box-shadow: 0 0 1px gray;
	-webkit-border-radius: 3px;
	-moz-border-radius: 3px;
	-ms-border-radius: 3px;
	-o-border-radius: 3px;
	border-radius: 3px;
	transition: padding 0.5s ease-in-out;
	-moz-transition: padding 0.5s ease-in-out;
	-webkit-transition: padding 0.5s ease-in-out;
}
.text-post {
	color: #000;
}

.pageTitle {
	padding-top: 70px;
	padding-bottom: 70px;
}

.page-title {
	color: white;
	margin: 5px 0 0 0;
	font-size: 30px;
	font-weight: 800;
}

.page-title {
	color: white;
	margin: 5px 0 0 0;
	font-size: 30px;
	font-weight: 800;
}
.home-intro-content {
	padding: 11em 0;
	text-align: center;
}
.home-intro-content h2 {
	font-size: 36px;
	font-weight: 800;
	color: white;
}
.home-intro-content p {
	margin: 55px 0;
	font-size: 18px;
	line-height: 32px;
}
@media (max-width: 991px) {
	.site-header {
		padding: 17px 0;
		position: relative !important;
	}
	.first-widget {
		margin-top: -30px;
		height: 60vh;
	}
}
@media (max-width: 767px) {
	.parallax {
		background-position: center center !important;
	}
	.parallax-text {
		width: 100%;
	}
	.cta .cta-title {
		display: block;
		margin-bottom: 30px;
	}

	.pageTitle {
		text-align: center;
	}
	.pageTitle .text-right {
		text-align: center;
	}
}
</style>
