<template>
    <button 
        @click="scrolltop" 
        id="btnUp" 
        class="hidden">
            <img src="@/static/img/up.svg" alt="">
            <span class="sr-only">Retour en haut</span>
    </button>
</template>

<script>
export default {

    methods: {

        scrolltop () {

            window.scroll({
                top: 0, 
                left: 0, 
                behavior: 'smooth'
            });

        }
    }
}
</script>