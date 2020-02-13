<template>
  <div class="about-card">
    <div class="card-title">
    	<img height="100px" src="https://vignette.wikia.nocookie.net/paradise-bay/images/5/5f/Avatar-Finn.png/revision/latest?cb=20170328211458" alt="avatar" class="avatar">
    	<div class="title-text-content">
    		<p>About Me</p>
    		<h2>Mahmudul Hasan</h2>
    	</div>
    </div>
    <div class="card-content">
    	<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
    	<table width="100%">
    		<tr>
    			<th>Requirement</th>
    			<th>Solution</th>
    		</tr>
    		<tr>
    			<td>Design</td>
    			<td>Photoshop, XD, Figma, Canva</td>
    		</tr>
    		<tr>
    			<td>Front-end</td>
    			<td>React.js, Vue.js, Nuxt.js, HTML, CSS, JavaScript</td>
    		</tr>
    		<tr>
    			<td>Back-end</td>
    			<td>Node.js, Express.js, Mongo, GraphQL</td>
    		</tr>
    		<tr>
    			<td>ML</td>
    			<td>Node.js, Express.js, Mongo, GraphQL</td>
    		</tr>
    		<tr>
    			<td>Shop</td>
    			<td>Node.js, Express.js, Mongo, GraphQL</td>
    		</tr>
    	</table>
    	<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>

    	<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
    </div>
  </div>
</template>

<style lang="sass" scoped>
	.about-card
		background: #333
		padding: 3em
		border-radious: 10px
		color: white
		.card-title
			display: flex
			align-items: center
			background: #222 
			border-radious: 10px
			.avatar
				border-radious: 50%
				margin: 0 30px
			.title-text-content
				p
					margin-bottom: 0
					color: rgb(210, 210, 210)
				h2
					margin-top: 0
	.card-content p
		line-height: 1.5
		margin: 30px auto
	table
		border-spacing: 0px
		margin: 50px auto
		tr th, tr td
			border: 1px solid white
			border-top: none
			padding: 10px
			text-align: center
			&:first-of-type
				border-left: none
			&:nth-of-type(2)
				border-right: none

</style>