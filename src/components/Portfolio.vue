<template>
    <section class="bg-light" id="portfolio">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center">
            <h2 class="section-heading text-uppercase">Portfolio</h2>
            <h3 class="section-subheading text-muted">Here are some free lance and some personal projects. Enjoy!</h3>
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
                img: 'vuejs.jpg',
                caption: 'Vue.js project',
                title: 'Portfolio',
                url: 'https://github.com/matiasdavidson/vue-portfolio-matiasdavidson'
            },
                        {
                img: 'vuejs.jpg',
                caption: 'Vue.js project',
                title: 'Crytocurrency web',
                url: 'https://matias-davidson-vue-cryptoworld.netlify.app/'
            },
            {
                img: 'vuejs.jpg',
                caption: 'Vue.js project',
                title: 'Weather app (Mobile for now)',
                url: 'https://vue-wheather-mobile-project.netlify.app/'
            },
            {
                img: 'kahlo.png',
                caption: 'Kahlo Agency',
                title: 'Front End development for Frigo®',
                url: 'https://www.frigolottaricotta.com/'
            },
            {
                img: 'kahlo.png',
                caption: 'Kahlo Agency',
                title: 'Front End development for Frigo®',
                url: 'https://www.fchsnackstyle.com/'
            },
            {
                img: 'coderhouse.jpg',
                caption: 'Project for Coderhouse',
                title: 'Starting a React Native project',
                url: 'https://github.com/matiasdavidson/react-native-project-start'
            },
            {
                img: 'digitalhouse.jpg',
                caption: 'Project for Digital House',
                title: 'Natural products ecommerce (Laravel)',
                url: 'https://github.com/matiasdavidson/laravel-elrestodeliceberg-project'
            }
        ]
    })
}
</script>

<style lang="css">

</style>


