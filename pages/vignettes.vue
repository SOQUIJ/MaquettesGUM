<template>
<div>

<navbar />
    <main class="container vh-100">
        <div class="vignettes container-1110">
            
            <H1>Lorem ipsum dolor sit amet.</H1>

            <ul>
                <li>
                    <a href="">
                        <div class="inner">
                            <img src="../static/img/domicile_bien_argent.png" aria-hidden="true" alt="Image décorative">
                            <h2>Domicile, Biens, Argent</h2>
                            <p>Partage des biens, Pension alimentaire pour ex-conjoint, Aides gouvernementales</p>
                        </div>
                    </a>
                </li>
                <li>
                    <a href="">
                        <div class="inner"> 
                            <img src="../static/img/enfant.png" aria-hidden="true" alt="Image décorative">
                            <h2>Enfant</h2>
                            <p>Annonce de la séparation, Pension alimentaire pour enfants, Garde, Vie quotidienne et éducation</p>
                        </div>
                    </a>
                </li>
                <li>
                    <a href="">
                        <div class="inner"> 
                            <img src="../static/img/adapter_separation.png" aria-hidden="true" alt="Image décorative">
                            <h2>S'adapter à la séparation</h2>
                            <p>S’organiser, Communiquer avec son ex, Émotions</p>
                        </div>
                    </a>
                </li>           
                <li>
                    <a href="">
                        <div class="inner"> 
                            <img src="../static/img/mediation.png" aria-hidden="true" alt="Image décorative">
                            <h2>Médiation</h2>
                            <p>Déroulement, Préparation, Trouver un médiateur</p>
                        </div>
                    </a>
                </li>



            </ul>
            
        </div>     
    </main>

</div>

</template>

<script>

export default {
    head: {
        bodyAttrs: {
            class: 'intro'
        }
    }
}
</script>

<style lang="scss">

    body.intro {
        background: none;

        main.container {
            
            .vignettes {

                margin: 0 auto;

            }

        }
    }
    
</style>