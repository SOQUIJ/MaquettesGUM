<template>
    <form role="search">

        <label>
            <img class="loupe" v-if="searchNotVisible" src="../static/img/search.svg" aria-hidden="true" alt="Loupe" />
            <span class="sr-only">Chercher</span>
            <input @focus="hideImg" @blur="hideImg" type="search" ref="input" placeholder="Chercher toutes les ressources">
        </label>
        <img v-if="!searchNotVisible" @click="dicterRecherche" role="button" class="microphone" src="../static/img/microphone-solid.svg" alt="Dicter votre recherche" />
        <button type="submit" class="sr-only">Soumettre</button>
        
    </form>

</template>

<script>
export default {

    data(){
        return {
            searchNotVisible: true
        }
    },
    methods: {

        hideImg () {
            this.searchNotVisible = !this.searchNotVisible;
        },
        dicterRecherche () {
            this.$refs["input"].focus();
        }
    }    
}
</script>

<style lang="scss">

    form[role="search"] {

        position: relative;

        img.loupe {
            cursor:pointer;
        }

        img.microphone {

            height: 18px;
            position: absolute;
            right: 16px;
            top: 22px;

        }

        input[type="search"] {
            width: 0;
            border: none;
            outline: none;
            background: #FFFFFF url(../static/img/search-filigrane.png) no-repeat 20px;
            padding: 18px 0 18px 0;
            border-radius: 30px;
            transition: width .2s ease-in-out, padding .2s;

            &:focus, &:active {
                width: 340px;
                padding: 18px 18px 18px 50px;
            }
        }
    }
 
</style>