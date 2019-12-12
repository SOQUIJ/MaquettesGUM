<template>
    <div class="accueil">
        <navbar />
        <div class="container">
            <h1>Bienvenue</h1>

            <p>
                <nuxt-link to="formulaire">Formulaire</nuxt-link>
            </p>

        </div>
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

<style lang="scss" scope>

.accueil {

    .breadcrumb {
        display: none;
    }

    .navigation-principale {
        background-color: #095797;
        a {
            color: #FFFFFF;
        }
    }

    body {
        background-image: none;
    }

    h1 {
        color: #223654;
    }

}



</style>