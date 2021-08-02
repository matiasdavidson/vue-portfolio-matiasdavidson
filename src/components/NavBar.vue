<template>
	<nav class="navbar navbar-expand-lg navbar-dark fixed-top" id="mainNav">
		<div class="container">
			<a class="navbar-brand js-scroll-trigger" href="#page-top"
				>Matias Davidson</a
			>
			<button
				class="navbar-toggler navbar-toggler-right"
				type="button"
				data-toggle="collapse"
				data-target="#navbarResponsive"
				aria-controls="navbarResponsive"
				aria-expanded="false"
				aria-label="Toggle navigation"
			>
				Menu
				<i class="fas fa-bars"></i>
			</button>
			<div class="collapse navbar-collapse" id="navbarResponsive">
				<ul class="navbar-nav text-uppercase ml-auto">
					<li class="nav-item">
						<a
							@click="collapseMenu"
							class="nav-link js-scroll-trigger"
							href="#about"
							>About me</a
						>
					</li>
					<li class="nav-item">
						<a
							@click="collapseMenu"
							class="nav-link js-scroll-trigger"
							href="#portfolio"
							>Portfolio</a
						>
					</li>
					<li class="nav-item">
						<a
							@click="collapseMenu"
							class="nav-link js-scroll-trigger"
							href="#experience"
							>Experience</a
						>
					</li>
					<li class="nav-item">
						<a
							@click="collapseMenu"
							class="nav-link js-scroll-trigger"
							href="#education"
							>education</a
						>
					</li>
					<li class="nav-item">
						<a
							@click="collapseMenu"
							class="nav-link js-scroll-trigger"
							href="#skills"
							>skills</a
						>
					</li>
					<a
						@click="collapseMenu"
						style="align-self:center"
						target="_blank"
						href="https://github.com/matiasdavidson"
						><img
							class="header-icon on-hover-zoom"
							src="../../public/img/GitHub-Mark-Light-120px-plus.png"
							alt=""
					/></a>
					<a
						@click="collapseMenu"
						style="align-self:center"
						target="_blank"
						href="https://www.linkedin.com/in/matias-davidson/"
						><img
							class="header-icon on-hover-zoom"
							src="../../public/img/linkedin-4-512.png"
							alt=""
					/></a>
					<a
						@click="collapseMenu"
						target="_blank"
						style="align-self:center"
						href="https://drive.google.com/file/d/1CBrpjBTOuyvkI_43SviaSbYBjY592JYy/view"
						><img
							class="header-icon on-hover-zoom"
							src="../../public/img/cv-icon.png"
							alt=""
					/></a>
				</ul>
			</div>
		</div>
	</nav>
</template>

<script>
export default {
	methods: {
		collapseMenu: function() {
			document.getElementById("navbarResponsive").classList.remove("show");
		},
	},
};
</script>

<style lang="css">
.container {
  max-width: 1800px !important;
}
</style>
