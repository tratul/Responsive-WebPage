<template>
	<section class="nav">
		<div class="nav-logo">
			<img height="200px" src="https://opallibya.com/wp-content/uploads/2019/01/avatar-256.png" alt="logo">
		</div>
		<div class="nav-menu">
			<ul class="nav-menu-list">
				<li class="nav-list-item">About me</li>
				<li class="nav-list-item">GitHub</li>
			</ul>
		</div>
	</section>
	</section>
</template>

<script>
	export default {

	}
</script>

<style lang="sass" scoped>
	.nav
		position: fixed
		left: 0
		top: 0
		bottom: 0
		background: #333
		display: flex
		flex-direction: column
		align-items: center
		width: 20vw
	.nav-logo
		margin: 100px auto
	.nav-menu
		color: white
	.nav-menu-list
		list-style: none
		padding: 0
		.nav-list-item
			background: #222
			padding: 18px 20px
			text-align: center
			margin: 10px auto
			cursor: pointer
			&:hover
				width: 100%
</style>