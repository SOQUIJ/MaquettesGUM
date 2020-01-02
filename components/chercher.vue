<template>
    <form role="search">

        <label>
            <img class="loupe" v-if="searchNotVisible" src="../static/img/search.svg" aria-hidden="true" alt="Loupe" />
            <span class="sr-only">Chercher</span>
            <input @focus="hideImg" @blur="hideImg" type="search" placeholder="Rechercher les resources du gum">
        </label>

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

        }

    }
    
}
</script>

<style lang="scss">

    form[role="search"] {

        img.loupe {

            cursor:pointer;
        }

        input[type="search"] {
            width: 0;
            border: none;
            outline: none;
            background: #FFFFFF url(../static/img/search-filigrane.png) no-repeat 20px;
            padding: 18px 0 18px 0;
            border-radius: 30px;
            transition: all .2s ease-in-out;

            &:focus, &:active {

                width: 315px;
                padding: 18px 10px 18px 60px;
            }
        }
    }
 
</style>