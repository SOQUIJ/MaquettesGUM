<template>
  <header id="navBar" class="fixed-top">
    <nav class="container navigation-principale" aria-label="Navigation principale">
      <div class="row">
        <div class="col-2 col-sm-4 col-md-4">
          <nuxt-link class="logo" to="/"><img src="@/static/img/logo.png" alt=""><span class="sr-only">Page d'accueil du GUM</span></nuxt-link>
        </div>
        <div class="col-10 col-sm-8 col-md-8 nav-droite">
          <ul>
              <li>
                <button><img src="@/static/img/search.svg" alt=""><span class="sr-only">Chercher sur ce site</span></button>
              </li>
              <li>
                <a href="#">Nous joindre</a>
              </li>
              <li>
                <a href="#">English</a>
              </li>
              <li>
                <button><img src="@/static/img/burger.svg" alt=""><span class="sr-only">Ouvrir le menu</span></button>
              </li>
            </ul>
        </div>
      </div>
    </nav>
    <nav aria-label="breadcrumb" class="bg-qc-ca">
      <div class="container">
        <ol class="breadcrumb container">
          <li class="breadcrumb-item">
            <nuxt-link to="/">Accueil</nuxt-link>
          </li>
          <li class="breadcrumb-item"><a href="#">Famille</a></li>
          <li class="breadcrumb-item active" aria-current="page">Divorce</li>
        </ol>
        <formRecherche></formRecherche>
      </div>   
    </nav>
      <div class="progress-container">
        <div class="progress-bar" id="myBar"></div>
      </div>
  </header>    
</template>

<script>

import formRecherche from '@/components/chercher'

export default {
  components: {
    formRecherche
  },
  mounted () {

    this.animateElementsOnScroll();   

  },
  methods: {

    animateElementsOnScroll() {

      var elNavBar = document.getElementById('navBar'),
          elBtnUp = document.getElementById('btnUp');

      document.addEventListener("scroll", function() {
          if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
              /*navBar.className = ('fixed-top bg-white');*/
              btnUp.className = ('visible')
          } else {
             /* navBar.className =  ('fixed-top');*/
              btnUp.className = ('')
          }

        var winScroll = document.body.scrollTop || document.documentElement.scrollTop,
            height = document.documentElement.scrollHeight - document.documentElement.clientHeight,
            scrolled = (winScroll / height) * 100;

        document.getElementById("myBar").style.width = scrolled + "%";


      });

    }

  }    
}
</script>

<style lang="scss">

header#navBar {

  background: white;

  nav[aria-label="breadcrumb"] > .container {

    // Positionner le formulaire de recherche dans le header
    position: relative;
    form[role="search"] {
        position: absolute;
        top: 10px;
        right: 20px;
    }
  }
}





  
</style>

