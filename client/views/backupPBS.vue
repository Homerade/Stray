<template>
	<div class="container-fluid"> 

		<router-link to='/products-all'>
			<section class="summer row">						
				<div class="col-lg-12">	
					<span class="textLeft">SUMMER</span>				
					<img src="assets/images/prodBySeas/summer_cuke.jpg" class="img-fluid">				
				</div>								
			</section>
		</router-link>	

		<router-link to='/products-all'>
			<section class="fall row">
				<div class="col-lg-12">
					<img src="assets/images/prodBySeas/fall_leaf.jpg" class="img-fluid">
					<span class="textRight">FALL</span>
				</div>
			</section>
		</router-link>

		<router-link to='/products-all'>
			<section class="winter row">
				<div class="col-lg-12">			
					<span class="textLeft">WINTER</span>		
					<img src="assets/images/prodBySeas/winter_artichoke.jpg" class="img-fluid">					
				</div>	
			</section>	
		</router-link>

		<router-link to='/products-all'>
			<section class="spring row">
				<div class="col-lg-12">
					<img src="assets/images/prodBySeas/spring_scene.jpg" class="img-fluid">
					<span class="textRight">SPRING</span>
				</div>	
			</section>
		</router-link>

	</div>	
</template>

<style type="text/css">

	@import '/assets/fonts/Wendy_LP_Bold.ttf';
	@import '/assets/fonts/pt-mono/PTMono.ttf';
	/* @import '/css/component.css'; */
	@import url('https://fonts.googleapis.com/css?family=Caveat|Kalam|Patrick+Hand');


	@font-face {
		font-family: 'Wendy LP Bold';
		src: url('/fonts/Wendy_LP_Bold.ttf') format('ttf');
	}

	@font-face {
		font-family: 'Wendy LP Bold';
		src: url('/assets/fonts/pt-mono/PTMono.ttf') format('ttf');
	}

	.row, .col-lg-12 {
		padding: 0;
	}

	a:hover {
		text-decoration: none;
	}

	/* .textLeft {
		line-height: 40vh;
		margin-left: 30vw;
	}

	.textRight {
		margin-left: 7vw;
	} */

	.summer img {
		max-width: 30%;
		float: right;
	}

	.summer {
		background-color: #d6fffc;		
		font-family: 'Kalam';
		font-size: 12vh;
		color: white;
		text-shadow: -1px 0 #d3d3d3, 0 1px #d3d3d3, 1px 0 #d3d3d3, 0 -1px #d3d3d3;
	}

	.fall img {
		max-width: 30%;		
	}

	.fall {
		background-color: #f6dfd2;
		text-decoration: none;
		font-family: 'Kalam';
		font-size: 12vh;
		color: white;	
		text-shadow: -1px 0 #d3d3d3, 0 1px #d3d3d3, 1px 0 #d3d3d3, 0 -1px #d3d3d3;
	}

	.winter img {
		max-width: 30%;
		float: right;
	}

	.winter {
		background-color: #e5eaef;
		font-family: 'Kalam';
		font-size: 12vh;
		color: white;
		text-shadow: -1px 0 #d3d3d3, 0 1px #d3d3d3, 1px 0 #d3d3d3, 0 -1px #d3d3d3;
	}

	.winterText {
		line-height: 40vh;
	}

	.spring img {
		max-width: 30%;
	}

	.spring {
		background-color: #e0f8e3;
		font-family: 'Kalam';
		font-size: 12vh;
		color: white;	
		text-shadow: -1px 0 #d3d3d3, 0 1px #d3d3d3, 1px 0 #d3d3d3, 0 -1px #d3d3d3;
	}

	section img {
		height: 40vh;
	}

</style>