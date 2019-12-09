<template>
  <header class="fixed-top">
    <nav class="container navigation-principale" aria-label="Navigation principale">
      <div class="row">
        <div class="col-2 col-sm-4 col-md-4 bg-primary text-white">
          <a href="#" class="logo"><img src="@/static/img/logo_white.png" alt=""><span class="sr-only">Page d'accueil du GUM</span></a>
        </div>
        <div class="col-10 col-sm-8 col-md-8 bg-white nav-droite">

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
      <ol class="breadcrumb container">
        <li class="breadcrumb-item"><a href="#">Accueil</a></li>
        <li class="breadcrumb-item"><a href="#">Famille</a></li>
        <li class="breadcrumb-item active" aria-current="page">Divorce</li>
      </ol>
    </nav>
  </header>    
</template>

<script>
export default {
    
}
</script>

