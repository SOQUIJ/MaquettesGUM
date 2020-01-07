<template>
    <div class="accueil">
        <main class="container">

            <div class="row">
                <div class="col-md-4 col-gauche bg-primary">
                    <div class="inner">
                        <h1>Maquettes</h1>
                    </div>                   
                </div>
                <div class="col-md-8 col-droite">
                    <article>
                        <h2>Listes des pages</h2>
                        <ul>
                           <li><nuxt-link to="formulaire">Formulaire</nuxt-link></li> 
                           <li><nuxt-link to="information">Information qualifiée</nuxt-link></li>
                           <li><nuxt-link to="nonqualifie">Information non qualifiée</nuxt-link></li>
                           <li><nuxt-link to="vignettes">Vignettes</nuxt-link></li>
                        </ul>

                    </article>
                </div>
            </div>

        </main>
    </div>
</template>

<script>

export default {

    head: {

        bodyAttrs: {
            class: 'home'
        }
    }
}
</script>

<style lang="scss">


    body.home  {

        padding-top: 0;

        header {
            position: static !important;

        }

        main {

            padding-bottom: 120px;

            .col-gauche {

                .inner {
                    position: static;
                }

            }


        }

        
    }

</style>