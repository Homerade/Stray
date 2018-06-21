<template>
	<div class="container-fluid"> 

	<!-- like the others:	 -->
		<router-link to='/products-all'>
			<section class="summer row">
				<div class="col-lg-12">						
					<span class="textLeft">Truffles</span>
					<span class="subTitle">& truffle products</span>
					<img src="assets/images/prodBySeas/summer_cuke.jpg" class="img-fluid">
				</div>	
			</section>
		</router-link>

	<!-- working on: -->
		<!-- <router-link to='/products-all'>
			<section class="summer row no-gutters">						
				<span class="col-lg-8 col-md-8">SUMMER</span>
				<img src="assets/images/prodBySeas/summer_cuke.jpg" class="img-fluid col-lg-4 col-md-4">							
			</section>
		</router-link>	 -->

		<!-- <router-link to='/products-all'>
			<section class="summer row">						
				<div>	
					<div class="col-8"><span class="textLeft">SUMMER</span></div>
					<div class="col-4"><img src="assets/images/prodBySeas/summer_cuke.jpg"></div>
				</div>								
			</section>
		</router-link> -->

		<router-link to='/products-all'>
			<section class="fall row">
				<div class="col-lg-12">
					<img src="assets/images/prodBySeas/fall_leaf.jpg" class="img-fluid">
					<span class="textRight">mushrooms</span>
					<span class="subTitle">local & imported</span>
				</div>
			</section>
		</router-link>

		<router-link to='/products-all'>
			<section class="winter row">
				<div class="col-lg-12">			
					<span class="textLeft">Microgreens</span>
					<span class="subTitle">from Brooklyn Grange</span>		
					<img src="assets/images/prodBySeas/winter_artichoke.jpg" class="img-fluid">					
				</div>	
			</section>	
		</router-link>

		<router-link to='/products-all'>
			<section class="winter row">
				<div class="col-lg-12">			
					<span class="textLeft">Produce</span>
					<span class="subTitle">from local farms</span>		
					<img src="assets/images/prodBySeas/winter_artichoke.jpg" class="img-fluid">					
				</div>	
			</section>	
		</router-link>

		<router-link to='/products-all'>
			<section class="spring row">
				<div class="col-lg-12">
					<img src="assets/images/prodBySeas/spring_scene.jpg" class="img-fluid">
					<span class="textRight">Specialty items</span>
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

	.summer {
		background-color: #d6fffc;
	}
	.summer {
		font-family: 'Kalam';
		font-size: 12vw;
		color: white;
		text-shadow: -1px 0 #d3d3d3, 0 1px #d3d3d3, 1px 0 #d3d3d3, 0 -1px #d3d3d3;
	}

	.summer img {
		float: right;
		max-width: 30%;
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
		height: 30vh;
	}

</style>