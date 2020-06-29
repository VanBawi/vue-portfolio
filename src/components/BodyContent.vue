<template>
	<div>
		<!-- start service -->
		<section id="service">
			<div class="service-width">
				<div class="row">
					<div class="col-md-12 text-center wow bounceIn">
						<h2>Tips & Tricks <i class="far fa-lightbulb"></i></h2>
						<hr class="line" />
						<h4>we specialize in web and mobile</h4>
					</div>
					<div class="col-md-6 col-sm-6">
						<div class="media">
							<div class="media-object media-left wow fadeIn" data-wow-delay="0.6s">
								<i class="far fa-keyboard"></i>
							</div>
							<div class="media-body">
								<h3 class="media-heading">Write down the Steps</h3>
								<p>
									Workforce HTML CSS Template is a mobile friendly site design layout with animated
									transitions. You can feel free to download and edit this for your sites.
								</p>
							</div>
						</div>
					</div>
					<div class="col-md-6 col-sm-6">
						<div class="media">
							<div class="media-object media-left wow fadeIn" data-wow-delay="0.6s">
								<i class="fas fa-fill-drip"></i>
							</div>
							<div class="media-body">
								<h3 class="media-heading">Implement the Codes</h3>
								<p>
									Please spread a word to your friends about templatemo site. It would be helpful.
									Credit goes to
									<a rel="nofollow noopener" href="https://pixabay.com">Pixabay</a> for images used
									in this template.
								</p>
							</div>
						</div>
					</div>
					<div class="col-md-6 col-sm-6">
						<div class="media">
							<div class="media-object media-left wow fadeIn" data-wow-delay="0.6s">
								<i class="fas fa-laptop-code"></i>
							</div>
							<div class="media-body">
								<h3 class="media-heading">Style the Entire Web</h3>
								<p>
									This is a CSS layout with Bootstrap v3.3.4 kit. Lorem ipsum dolor sit amet,
									consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt.
								</p>
							</div>
						</div>
					</div>
					<div class="col-md-6 col-sm-6">
						<div class="media">
							<div class="media-object media-left wow fadeIn" data-wow-delay="0.6s">
								<i class="fas fa-rocket"></i>
							</div>
							<div class="media-body">
								<h3 class="media-heading">Deply to Firebase</h3>
								<p>
									This is a CSS layout with Bootstrap v3.3.4 kit. Lorem ipsum dolor sit amet,
									consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt.
								</p>
							</div>
						</div>
					</div>
				</div>
			</div>
		</section>
		<!-- end service -->
		<!-- row -->

		<div class="row">
			<section class="tm-2-col-img-text col-md-12 tm-2-col-img-lg-right">
				<div class="col-xs-12 col-sm-12 col-md-12 col-lg-6 col-xl-6 tm-2-col-img">
					<img src="../assets/images/tv-background.jpg" alt="Image" class="img-fluid" />
				</div>

				<div class="col-xs-12 col-sm-12 col-md-12 col-lg-6 col-xl-6 tm-2-col-text">
					<h2 class="tm-2-col-text-title">Integer sed dictum lectus</h2>
					<p class="tm-2-col-text-description">
						Aliquam augue libero, convallis in vulputate vel, sodales sed purus. In non velit in
						eros bibendum pretium quis eu sapien. Donec sapien risus, hendrerit ut metus dignissim,
						pellentesque congue erat. Quisque tempor odio libero, non auctor odio suscipit eget.
					</p>
					<a href="#" class="tm-bordered-btn">Read More</a>
				</div>
			</section>
		</div>

		<!-- row -->

		<div class="row">
			<section class="tm-2-col-img-text tm-2-col-img-lg-left">
				<div class="col-xs-12 col-sm-12 col-md-12 col-lg-6 col-xl-6 tm-2-col-img">
					<img src="../assets/images/97.jpg" alt="Image" class="img-fluid" />
				</div>

				<div class="col-xs-12 col-sm-12 col-md-12 col-lg-6 col-xl-6 tm-2-col-text">
					<h2 class="tm-2-col-text-title">Integer sed dictum lectus</h2>
					<p class="tm-2-col-text-description">
						Aliquam augue libero, convallis in vulputate vel, sodales sed purus. In non velit in
						eros bibendum pretium quis eu sapien. Donec sapien risus, hendrerit ut metus dignissim,
						pellentesque congue erat. Quisque tempor odio libero, non auctor odio suscipit eget.
					</p>
					<a href="#" class="tm-bordered-btn">Read More</a>
				</div>
			</section>
		</div>
		<!-- row -->
	</div>
</template>

<script>
// import custom from './custom.js';

export default {};
</script>

<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Quicksand&display=swap');
/* start service */
h4 {
	padding: 15px;
}
#service {
	background: #ffffff;
	padding-top: 80px;
	padding-bottom: 80px;
	font-family: 'Quicksand', sans-serif;
}
#service .media {
	padding: 10px;
}
#service .media .fa {
	color: #55acee;
	font-size: 60px;
	margin-right: 20px;
	width: 65px;
	height: 65px;
}
#service .media .media-heading {
	font-weight: 600;
	font-size: 20px;
	padding-bottom: 10px;
}
.service-width {
	width: 70%;
	margin: 0 auto;
}
.media-body {
	line-height: 1.8;
}

.far {
	color: gold;
}

.fas,
.fa-keyboard {
	font-size: 2em;
	color: white;
	margin: 10px;
	padding: 15px;
	background-color: #2980b9;
	border-radius: 50%;
}
hr.line {
	width: 50px;
	margin: 0 auto;
	border: 2px solid #2980b9;
}

.bounceIn {
	transition: 0.4s ease-in-out;
}
/* 3. Image and text 2 column block
-------------------------------------*/

.tm-2-col-img-text {
	display: -webkit-flex;
	display: -ms-flexbox;
	display: flex;
	overflow: auto;
}

.tm-2-col-img {
	padding: 0;
	// border: 1px solid gray;
	margin: 0 auto;
}

.img-fluid {
	height: auto;
}

.tm-2-col-img-lg-right .tm-2-col-img {
	-webkit-order: 2;
	-ms-flex-order: 2;
	order: 2;
}

.tm-2-col-img-lg-right .tm-2-col-text {
	-webkit-order: 1;
	-ms-flex-order: 1;
	order: 1;
}

.tm-2-col-text {
	display: -webkit-flex;
	display: -ms-flexbox;
	display: flex;
	-webkit-align-items: flex-start;
	-ms-flex-align: start;
	align-items: flex-start;
	-webkit-flex-direction: column;
	-ms-flex-direction: column;
	flex-direction: column;
	-webkit-justify-content: center;
	-ms-flex-pack: center;
	justify-content: center;
	padding-left: 5%;
	padding-right: 5%;
}

.tm-2-col-text-title {
	color: #2980b9;
	font-size: 1.9rem;
	font-weight: 300;
	margin-bottom: 5%;
}

.tm-2-col-text-description {
	color: #2980b9;
	font-size: 1.4rem;
	font-weight: 300;
	line-height: 1.9;
	margin-bottom: 6%;
	width: 100%;
}

.tm-bordered-btn {
	background-color: transparent;
	border: 2px solid #2980b9;
	text-decoration: none;
	border-radius: 2.5rem;
	color: #81b4eb;
	display: inline-block;
	font-size: 1.5rem;
	font-weight: 400;
	padding: 0.6rem 2rem;
}

.tm-bordered-btn:hover,
.tm-bordered-btn:focus {
	color: white;
	background-color: #81b4eb;
}

/* 3. Image and text 2 column block
----------------------------------------*/
@media (max-width: 1600px) {
	.tm-2-col-text {
		padding-left: 5%;
		padding-right: 5%;
	}
}

@media (max-width: 1320px) {
	.tm-2-col-text {
		padding-left: 3%;
		padding-right: 3%;
	}

	.tm-2-col-text-description {
		font-size: 1.1rem;
		line-height: 1.6;
		margin-bottom: 4%;
	}

	.tm-bordered-btn {
		font-size: 1.2rem;
		padding: 0.5rem 2rem;
	}
}
</style>
