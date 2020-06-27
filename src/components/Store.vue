<template>
	<div class="">
		<store-header></store-header>
		<div class="items row ">
			<div class="item  col-md-auto">
				<img class="card-img-top" src="../assets/images/backpack.png" alt="Card image cap" />
				<div class="card-body">
					<a href="#" class="card-link btn btn-primary">Add to Cart</a>

					<a href="#" class="card-link"><i class="fas fa-heart"></i></a>
					<i class="fas fa-share-square"></i>
				</div>
			</div>
			<!-- <div class="item col-md-auto">
				<img class="card-img-top" src="../assets/images/backpack.png" alt="Card image cap" />
				<div class="card-body">
					<a href="#" class="card-link">Add to Cart</a>
					<a href="#" class="card-link"><i class="fas fa-heart "></i></a>
				</div>
			</div>
			<div class="item  col-md-auto">
				<img class="card-img-top" src="../assets/images/backpack.png" alt="Card image cap" />
				<div class="card-body">
					<a href="#" class="card-link">Add to Cart</a>
					<a href="#" class="card-link"><i class="fas fa-heart "></i></a>
				</div>
			</div>
			<div class="item  col-md-auto">
				<img class="card-img-top" src="../assets/images/backpack.png" alt="Card image cap" />
				<div c
				lass="card-body">
					<a href="#" class="card-link">Add to Cart</a>
					<a href="#" class="card-link"><i class="fas fa-heart"></i></a>
				</div> -->
			<!-- </div> -->
		</div>
	</div>
</template>

<script>
import StoreHeader from './StoreHeader';
export default {
	components: {
		'store-header': StoreHeader,
	},
};
</script>

<style lang="scss" scoped>
.items {
	margin: 0 auto;
	display: flex;
	justify-content: center;
}
.item {
	margin: 1%;
	width: 25rem;
}
img,
.card-body {
	border: 1px solid lightgrey;
	// margin: 0px 10px 0px 10px;
	// box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}
.card-body {
	display: flex;
	justify-content: space-between;
}
</style>
