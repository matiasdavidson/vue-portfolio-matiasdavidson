<template>
    <section id="portfolio">
      <div v-vue-aos="{animationClass:'fadeIn animated'}" class="container">
        <div class="row" data-aos="fade-up">
          <div class="col-lg-12 text-center">
            <h2 class="section-heading text-uppercase">Portfolio</h2>
            <h3 class="section-subheading text-muted">Here are some freelance and some personal projects. Enjoy!</h3>
          </div>
        </div>
        <div class="row">
          
            <div class="col-md-4 col-sm-6 portfolio-item" v-for="(obj, key) in portfolioJSON" :key="key">
                <a class="portfolio-link" target="_blank" :href="obj.url">
                    <div class="portfolio-hover">
                        <div class="portfolio-hover-content">
                            <i class="fas fa-plus fa-3x"></i>
                        </div>
                    </div>
                    <img class="img-fluid" :src="'/img/' + obj.img" alt="">
                <div class="portfolio-caption">
                    <h4>{{ obj.caption }}</h4>
                    <p class="text-muted">{{ obj.title }}</p>
                </div>
                </a>
            </div>
        </div>
      </div>
    </section>
</template>
<script>

export default {
    data: () => ({
        portfolioJSON: [
            {
                img: 'vista-bb-site.png',
                caption: 'Breaking Bad´s Site',
                title: 'Breaking Bad Site using its api (React project)',
                url: 'https://mati-breaking-bad-site.netlify.app/'
            },
            {
                img: 'vista-portfolio.png',
                caption: 'Resume',
                title: 'Vue.js project',
                url: 'https://github.com/matiasdavidson/vue-portfolio-matiasdavidson'
            },
                        {
                img: 'vista-crypto.png',
                caption: 'Cryptocurrency web',
                title: 'Vue.js project',
                url: 'https://matias-davidson-vue-cryptoworld.netlify.app/'
            },
            {
                img: 'vista-lotta.png',
                caption: 'Landing Page for Frigo®',
                title: 'JS, HTML, PHP, SCSS',
                url: 'https://github.com/matiasdavidson/Ricotta'
            },
            {
                img: 'vista-cheese.png',
                caption: 'Landing Page for Frigo®',
                title: 'JS, HTML, PHP, SCSS',
                url: 'https://github.com/matiasdavidson/Cheeseheads'
            },
            {
                img: 'vista-react-native.png',
                caption: 'Basic Spotify clone',
                title: 'Starting a React Native project',
                url: 'https://github.com/matiasdavidson/react-native-project-start'
            },
            {
                img: 'vista-vep.png',
                caption: 'Activist Organization web',
                title: 'Vue.js project',
                url: 'https://veganismoenparques.netlify.app/'
            },
            {
                img: 'vista-weather.png',
                caption: 'Weather app',
                title: 'Vue.js project',
                url: 'https://vue-wheather-mobile-project.netlify.app/'
            },
            {
                img: 'vista-erdi.png',
                caption: 'El Resto del Iceberg',
                title: 'Natural products ecommerce (Laravel project)',
                url: 'https://github.com/matiasdavidson/laravel-elrestodeliceberg-project'
            },
        ]
    })
}
</script>

<style lang="css">

</style>


