<template>
	<div class="contact-section">
		<div class="container">
			<div class="contact-content col-md-12 row">
				<div class="col-md-12 text-center wow bounceIn">
					<h2>Contact Me <i class="fas fa-id-card"></i></h2>
					<hr class="line" />
				</div>
				<div class="contact-content-left col-md-4">
					<div class="title">
						Fell free to keep in touch with me.
					</div>
					<div class="description">
						<div class="description-icon">
							<i class="fas fa-phone"></i>
							<p class="text-align">010-222-3333</p>
						</div>
						<div class="description-icon">
							<i class="far fa-envelope"></i>
							<p class="text-align">info@company.com</p>
						</div>
						<div class="description-icon">
							<i class="fas fa-globe"></i>
							<p class="text-align">www.company.com</p>
						</div>
					</div>
				</div>
				<div class="contact-content-right col-md-8">
					<div class="contact-form-input col-md-12">
						<div class="contact-form">
							<input type="text" placeholder="Your Name" class="form-control" />
							<input type="text" placeholder="Your Pone" class="form-control " />
						</div>
						<div class="contact-form">
							<input type="text" placeholder="Your Email" class="form-control" />
							<input type="text" placeholder="Your Subject" class="form-control" />
						</div>
					</div>
					<div class="message col-md-12">
						<textarea placeholder="Write something.." class="form-control"></textarea>
						<input type="submit" value="Send Message" class="form-control button fa-caret-right" />
					</div>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Quicksand&display=swap');
.contact-section {
	background-image: url('../assets/images/contact-image.jpg');
	background-repeat: no-repeat;
	background-size: cover;
	opacity: 0.7;
}
.text-center {
	padding-bottom: 4rem;
	font-family: 'Quicksand', sans-serif;
}
.contact-content {
	padding: 4rem;
}

.contact-form {
	display: grid;
	grid-template-columns: 1fr 1fr;
	justify-content: space-between;
	grid-gap: 1em;
	padding-bottom: 1.2em;
}

.message {
	display: grid;
	grid-template-rows: 2fr 1fr;
}

.button {
	margin-top: 1.2em;
	background-color: #2980b9;
	color: white;
	width: 14rem;
	border-radius: 1.5em;
	height: 3em;
}

.button:hover {
	color: white;
	background-color: #003772;
	width: 16rem;
	transition: all 0.5s ease-out;
}

.description-icon {
	display: flex;
}
.description-icon:hover {
	font-size: 1.1em;
	transition: all 0.3s ease-out;
}
.text-align {
	align-self: center;
	margin-top: 1em;
}
.fa-phone,
.fa-envelope,
.fa-globe {
	font-size: 1.5em;
	color: white;
	margin: 10px;
	padding: 15px;
	background-color: #2980b9;
	border-radius: 50%;
}
.fa-id-card {
	color: #2980b9;
}
hr.line {
	width: 50px;
	margin: 0 auto;
	border: 2px solid #2980b9;
}
</style>
