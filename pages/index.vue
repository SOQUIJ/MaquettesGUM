<template>
    <div class="accueil h-100">
        <navbar />
        <main class="container">

            <div class="row">
                <div class="col-md-4 col-gauche">

                    <h1>Bienvenue</h1>


                </div>
                <div class="col-md-6 col-droite">
                    <div class="inner">

                        <h2>Listes des pages</h2>
                        <ul>
                           <li><nuxt-link to="formulaire">Formulaire</nuxt-link></li> 
                           <li><nuxt-link to="information">Page d'information</nuxt-link></li>
                        </ul>

                    </div>
                </div>
            </div>

        </main>
    </div>
</template>

<script>
import navbar from "@/components/navbar"
export default {

    components: {
        navbar
    }
    
}
</script>

<style lang="scss" scoped>



.accueil {



    header {

        .navigation-principale {

            background-color: #095797;

            a {
                color: #FFFFFF;
            }
        }

        .breadcrumb {
            display: none;
        }        

    }

    main {

        .col-droite {

            .inner {

                padding-top: 105px;
                max-width: 70%;
            
            }
        }
    }
}



</style>