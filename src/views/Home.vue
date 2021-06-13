<template>
  <div class="home">
    <HeaderMaj />
    <HeroMaj />
    <WomenMaj />
    <InstaMaj />
    <PartnerMaj />
    <FooterMaj />

    
  </div>
</template>

<script>
import HeaderMaj from '@/components/HeaderMaj.vue'
import HeroMaj from '@/components/HeroMaj.vue'
import WomenMaj from '@/components/WomenMaj.vue'
import InstaMaj from '@/components/InstaMaj.vue'
import PartnerMaj from '@/components/PartnerMaj.vue'
import FooterMaj from '@/components/FooterMaj.vue'


export default {
  name: 'Home',
  components: {
    HeaderMaj,
    HeroMaj,
    WomenMaj,
    InstaMaj,
    PartnerMaj,
    FooterMaj,
  }, 
  
}
</script>
