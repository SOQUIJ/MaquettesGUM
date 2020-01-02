<template>

    <footer>
      
           <section class="footer-main">

               <div class="container">

                   <div class="row">
                        <div class="col-md-3">

                            <a href="#"><img class="mb-24 logo-gum-footer" src="../static/img/logo_footer.png" alt="Logo du GUM"></a>

                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus quia laborum atque numquam maxime dolorum maiores.</p>

                            <a href="#"><img src="../static/img/facebook-brands.svg" alt="facebook"></a>

                        </div>
                        <div class="col-md-3">
                            
                            <h3 class="mb-24">Sujets</h3>
                            <ul>
                                <li><a href="#">Divorce et Séparation</a></li>
                                <li><a href="#">Testament et mandat de protection</a> </li>
                                <li><a href="#">Succession</a></li>
                                <li><a href="#">Mariage</a></li>
                            </ul>
                            
                        </div>
                        <div class="col-md-3">
                            
                            <h3 class="mb-24">Support</h3>

                            <ul>
                                <li><a href="#">Bottin de ressources juridiques</a></li>
                                <li><a href="#">Aide à la recherche</a></li>
                                <li><a href="#">Nous joindre</a></li>
                            </ul>
                            
                        </div>
                        <div class="col-md-3">

                            <h3 class="mb-24">Avec la participation de</h3>

                                <p class="clearfix logos-participation">
                                    <a href="#"><img src="../static/img/educaloi.png" alt="Logo d'Éducaloi"></a>
                                    <a href="#"><img src="../static/img/ministere_justice.png" alt="Logo du ministère de la justice"></a>
                                </p>

                            <h3 class="mb-24">
                            Aider nous à améliorer notre site en partageant votre opinion :
                            </h3>

                            <a href="#">Donnez-nous vos commentaires</a>
                            
                        </div>
                   </div>
               </div>

           </section>

           <section class="footer-secondaire">

               <div class="container">

                    <ul>
                        <li><a href="#">Accessibilité</a></li>
                        <li><a href="#">Plan du site </a></li>
                        <li><a href="#">Accès à l’information</a></li>
                        <li><a href="#">Politique de confidentialité</a></li>
                        <li><a href="#">À propos de Québec.ca</a></li>
                    </ul>

                    <p><img src="../static/img/logo_qc-footer.png" alt="Logo du gouvernement du Québec"></p>

                    <p class="lien-gouv-quebec-footer"><a href="#">© Gouvernement du Québec, 2020. Propulsé par SOQUIJ</a></p>

                </div>
           </section>


    </footer>
</template>

<style lang="scss">

footer {
             
    position: relative;
    z-index: 1;
    
    section.footer-main {

        background: #1D2E47;
        color: white;           

        .container {            

            max-width: 1110px;
            padding: 120px 0;

            .logo-gum-footer {

                margin-top: 9px;
            }

            h3 {

                font-weight: bold;
                font-size: 18px;
                line-height: 28px;
                font-family: 'Open Sans', Courier, monospace
            }

            a, h3 {
                color: #FFFFFF;
            }

            a:hover {
                color: white;
                text-decoration: underline;
            }

            ul {

                list-style: none;
                margin:0;
                padding: 0;

                li {
                    margin-bottom: 24px;

                    &:nth-last-child() {
                        margin-bottom: 0;
                    }
                }
                
            }

            .logos-participation {

                margin-bottom: 24px;

                a:first-child {

                    float: left;

                }

                a:last-child {
                    float: right;
                }
            }

        }
    }

    section.footer-secondaire {

        background: #FFFFFF;

        .container {            

            max-width: 1110px;
            padding: 24px;
            text-align: center;

            ul {

                margin: 0;
                padding: 0;
                list-style: none;


                li {
                    display: inline;
                    margin: 0 24px;
                }

            }
        

        }      

    }

}
    
</style>