<template>
	<section class="nav">
		<div class="nav-logo">
			<img height="160px" src="https://opallibya.com/wp-content/uploads/2019/01/avatar-256.png" alt="logo">
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
	
</script>

<style lang="sass" scoped>
	.nav
		background: #333
		display: flex
		flex-direction: column
		justify-content: space-around
		align-items: center
		.nav-logo
			margin: 20px auto
		.nav-menu
			width: 100%
	.nav-menu-list
		list-style: none
		padding: 0
		display: flex
		margin: 0
		color: white
		li
			width: 50%
			text-align: center
			background: #555
			padding: 10px 0
			cursor: pointer
			transmition: background 300ms ease-inout
			&:hover
				background: #333
			&:first-of-type
				border-bottom: 5px solid #222

</style>