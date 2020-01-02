<template>
  <div class="h-100">
    <gumHeader />
    <nuxt />
    <gumFooter />
  </div>
</template>
<script>
import gumHeader from '@/components/navbar'
import gumFooter from '@/components/footer'
export default {

  components:{
    gumHeader,
    gumFooter
  }
  
}
</script>