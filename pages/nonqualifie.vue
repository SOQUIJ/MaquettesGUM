<template>
<div>
    <navbar />
    <div class="container">
        <div class="row">
            <div class="col-md-4 col-gauche text-white">
                <div class="inner">
                    <h1>Domicile: qui peut rester, qui doit partir</h1>
                    <p>Ce contenu s'adresse aux ...</p>
                    <nav>
                        <ul>
                            <li class="animated delay-1 fadeInLeft"><a @click="scrollIt('couples-maries', $event);" href="#couples-maries" :class="{'actif disabled':marier}"><span class="triangle" aria-hidden="true"></span>Couples mariés</a></li>
                            <li class="animated delay-2 fadeInLeft"><a @click="scrollIt('conjoints-de-fait', $event);" href="#conjoints-de-fait" :class="{'actif disabled':conjoint}"><span class="triangle" aria-hidden="true"></span>Conjoints de faits</a></li>
                        </ul>
                    </nav>
                </div>
            </div>
            <div class="col-md-8 col-droite">
                <article class="animated fadeInUp delay-3">
                    <section>
                        <h2 id="couples-maries">Couples mariés</h2>
                        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Rem est incidunt libero ex cum ad eius ipsum, adipisci blanditiis placeat illum quibusdam, reiciendis quis velit iure voluptatum pariatur ea commodi obcaecati nisi vitae. Reiciendis perferendis quos necessitatibus minima sapiente nisi, magnam est ut, odio eveniet laborum nihil quidem. Necessitatibus maxime quos exercitationem velit nam inventore illo maiores tempora totam aliquam facere excepturi ipsam neque illum, consectetur sit. Facilis praesentium exercitationem qui natus earum accusantium dolorum quis accusamus, veritatis sequi. A.</p>
                        <h3>Sous titre quelconque de niveau 3</h3>
                        <p>Ratione, tempore laboriosam id praesentium veniam totam? Odio nihil architecto est ut quisquam perferendis expedita rem eos sit delectus numquam quasi ex at, dolorum doloremque recusandae, aperiam qui rerum ipsa facilis. Totam officia molestiae distinctio repellendus quibusdam ducimus voluptas ipsam blanditiis laboriosam, voluptate ea fuga eaque temporibus libero officiis! Libero deserunt, aspernatur sint quidem accusamus eligendi obcaecati quae at adipisci ipsum nulla quam, consequuntur, inventore ipsam sunt. Illo porro repellendus suscipit, voluptatibus inventore laboriosam reprehenderit explicabo aperiam minima magni voluptates.</p>
                        <p>Officia magnam id ipsa beatae, corrupti eligendi nostrum fugiat nesciunt vero? Suscipit corrupti tempora provident quae, ea numquam officia veniam, illum fugiat iure velit quibusdam modi eius maiores rem veritatis assumenda accusamus. Quaerat, harum! Optio qui nemo asperiores praesentium, quis quo expedita magni repellendus quam, at tenetur veniam accusamus labore facilis natus quaerat ipsa consectetur nulla dolor sed harum. Sed quod aliquam sint eos necessitatibus repellat obcaecati quibusdam blanditiis, dolores minima sit, illum laboriosam ipsam? Magni consequatur unde dignissimos minus!</p>
                        <h3 class="titre-info">Lectures</h3>
                        <p>Doloremque nesciunt rerum nisi eaque consequatur ad modi laudantium, dolores porro vero, nihil beatae soluta aliquam quae alias aperiam, nam officia repudiandae voluptatem molestiae sequi necessitatibus repellat facere. Nam reprehenderit, ea esse amet, magni commodi ex minus magnam neque dolores voluptatibus molestias expedita optio, minima voluptates a illo iure natus sequi autem ipsa. Eaque rem qui, iusto commodi quam impedit distinctio est eius expedita ipsam. Ex quo consequuntur cumque sint suscipit illo officia aspernatur enim assumenda autem? Consequuntur, tempora sit.</p>
                        <p>Voluptatibus tempora recusandae, provident vel voluptatem aliquam! Non, animi harum, nihil mollitia laboriosam reiciendis odit vero praesentium accusamus error doloribus dicta eligendi officiis cumque perferendis enim! Debitis, repellendus. Omnis nemo animi dicta aut quae veritatis ex aperiam! Ullam soluta consequatur nesciunt corporis quas velit, impedit numquam ipsa ab sunt? Dicta odit minima esse corporis repudiandae? Unde cumque distinctio, nesciunt rem, voluptatum libero exercitationem nulla adipisci dolores perferendis voluptatem id eaque commodi voluptates veritatis inventore laborum fugit eligendi ullam debitis? Veniam.</p>                       
                    </section>
                    <section>
                        <h2 id="conjoints-de-fait">Conjoints de fait</h2>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Expedita distinctio consectetur est! Tempore error dolore commodi totam, recusandae fugiat ea hic rerum sint fugit quia consequuntur ut mollitia aspernatur porro repellendus. Atque enim inventore voluptas aliquid! Beatae nisi at hic aspernatur quisquam voluptas labore tempore quidem, dignissimos itaque inventore nobis necessitatibus! Neque, iste dolorem rerum repellendus sint nulla officia ducimus tenetur labore, officiis reprehenderit, vitae nesciunt nihil fuga? Eveniet, placeat. Sequi facere suscipit quidem placeat, odit pariatur soluta rerum enim.</p>
                        <p>Iste velit ut aspernatur laudantium autem ullam incidunt obcaecati odio similique aperiam rerum dolores et atque saepe quasi, corporis ex? Molestias, inventore? Esse quam perspiciatis, aliquam deleniti voluptate ipsam repellat culpa sequi odit fuga labore animi eos eligendi alias optio itaque dicta nisi sunt debitis similique assumenda consequuntur. Quos error non cum. Soluta aliquam eveniet accusamus rerum deleniti quia nulla ipsam odio nisi consequuntur at praesentium, temporibus, quasi repellat totam ex earum rem libero sint debitis tenetur. Et, esse quo!</p>
                        <p>Labore sit laborum numquam sint, maiores corporis voluptas blanditiis saepe perferendis inventore sapiente accusantium veniam ipsam? Maxime, ab perspiciatis, similique consectetur tempore quisquam fuga ut dolor dolorem commodi dolore placeat esse a enim minima sint eos reiciendis reprehenderit, iure accusamus repellendus quos ea? Et quod mollitia facilis minus? Rem a ad omnis aut id, eius nulla dolorum qui, inventore nostrum ex, dolores pariatur molestias. Porro unde at sequi! Tenetur ab libero culpa blanditiis at expedita amet commodi cumque, veritatis incidunt.</p>
                        <p>Nam dolorem voluptatibus dolores alias quas ad repellat amet, quia ducimus. Non, vel iste reprehenderit veniam dolorum id iusto omnis tempore eligendi vitae? Voluptatum, nihil dicta suscipit magni, laborum placeat quis reiciendis quidem a autem delectus dolore sequi? Cum quis similique voluptate est obcaecati enim ullam facilis et ad molestias! Doloremque itaque, saepe perspiciatis iure blanditiis ab aperiam explicabo enim. Temporibus, beatae. Obcaecati delectus quae, optio odit quod eum, fuga explicabo earum sint voluptas numquam vero recusandae consequuntur ipsa qui?</p>
                        <p>Tenetur illo iste beatae repudiandae totam aut alias dolorum aliquid? Aliquam magnam velit ratione, officia enim reprehenderit! Et rerum nemo amet labore voluptas magni at dolor hic assumenda soluta excepturi quisquam veritatis explicabo ipsum velit, eveniet debitis dolorem consequuntur dolorum, pariatur sed quod optio. Optio, aperiam autem. Cumque delectus consequatur quisquam repudiandae possimus ipsum alias tenetur culpa officia, ipsam provident ratione hic magnam excepturi eos cum numquam eaque cupiditate. Reiciendis iure nulla necessitatibus voluptatum, fugiat aspernatur. Beatae illum ad labore.</p>
                    </section>
                </article>
                <btnup />
            </div>
        </div>
    </div>
</div>
</template>
<script>

import btnup from '@/components/buttonup'

export default {

    data() {
      
        return {
 
            marier: true,
            conjoint: false

        }
               
    },
    components: {

        btnup
    },

    methods: {

        scrollIt(destination) {

            /* Pour désactiver le lien actif */
             this.marier = !this.marier;
             this.conjoint = !this.conjoint;

            /* Déterminer la position de l'ancre dans la page relativement au bas de la barre de navigation */
            var el = document.getElementById(destination),
                topPos = el.offsetTop - 92;      

            setTimeout(() => {
                document.body.scrollTop = topPos; // Pour Safari et Edge
                document.documentElement.scrollTop = topPos; // Pour les autres
            }, 10);              
        }
    }
}
</script>


<style lang="scss">

.col-gauche {

    ul {

        margin-top: 45px;

        li {
            margin-bottom: 16px;


            a { 
                color: #F09686;
                position: relative;
                left: 0;
                
                .triangle {
                    display: inline-block;
                    position: relative;
                    top: 1px;
                    margin-right: 8px;
                    width: 0;
                    height: 0;
                    border-right: 10px solid transparent;
                    border-left: 10px solid transparent;
                    border-bottom: 16px solid #F09686;
                    transition: all .3s ease-in-out;

                    &:after {
                        content: "";
                        display:inline-block;
                        position:absolute;
                        width: 0;
                        height: 0;    
                        top: 4px;
                        left: -6px;
                        border-left: 6px solid transparent;
                        border-right: 6px solid transparent;
                        border-bottom: 10px solid #223654;
                    }

                }

                &:hover  {

                    text-decoration: none;

                    .triangle {
                        top: 4px;
                        transform: rotate(90deg);
                        margin-right: 14px;
                    }       
                } 


            }

            a.actif {

                color: #FFFFFF;

                .triangle {
                    top: 4px;
                    border-bottom: 16px solid #FFFFFF;
                    transform: rotate(90deg);
                    margin-right: 14px;
                }

            }


            a.disabled {
                pointer-events: none;
            }
    
        }        

    }

}


</style>