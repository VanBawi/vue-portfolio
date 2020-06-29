<template>
	<div>
		<footer class="site-footer ">
			<div class="container">
				<div class="row">
					<div class="">
						<nav class="footer-nav clearfix">
							<ul class="footer-menu">
								<li><a href="index.html">Home</a></li>
								<li><a href="portfolio.html">Portfolio</a></li>
								<li><a href="blog.html">Blog Posts</a></li>
								<li><a href="archives.html">Shortcodes Shortcodes</a></li>
								<li><a href="contact.html">Contact</a></li>
							</ul>
						</nav>
						<nav class="footer-nav clearfix">
							<ul class="footer-menu">
								<li><a href="index.html">Home</a></li>
								<li><a href="portfolio.html">Portfolio</a></li>
								<li><a href="blog.html">Blog Posts</a></li>
								<li><a href="archives.html">Shortcodes</a></li>
								<li><a href="contact.html">Contact</a></li>
							</ul>
						</nav>
					</div>
				</div>
				<!-- /.row -->
				<div class="row">
					<div class="">
						<p class="copyright-text">Copyright &copy; 2084 Company Name | Design: templatemo</p>
					</div>
				</div>
			</div>
		</footer>
	</div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.site-footer {
	background-color: #f1f4f5;
	padding: 40px 0;
	color: #aaaaaa;
	font-family: 'Raleway', sans-serif;
}

.footer-menu li {
	display: inline-block;
	margin: 0 20px;
}
.footer-menu li a {
	color: #aaaaaa;
	font-size: 13px;
	text-transform: uppercase;
	font-weight: 700;
}
.footer-menu li a:hover {
	color: #00a8d6;
}

.copyright-text {
	margin-top: 30px;
	font-weight: 700;
	text-transform: uppercase;
	font-size: 13px;
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
