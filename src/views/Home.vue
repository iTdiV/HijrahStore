<template>
  <div class="home">
    <HeaderHijrah />
    
    <HeroHijrah />

    <BannerHijrah />

    <InstaHijrah />

    <PartnerHijrah />

    <FooterHijrah />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderHijrah from '@/components/HeaderHijrah.vue'

import HeroHijrah from '@/components/HeroHijrah.vue'

import BannerHijrah from '@/components/BannerHijrah.vue'

import InstaHijrah from '@/components/InstaHijrah.vue'

import PartnerHijrah from '@/components/PartnerHijrah.vue'

import FooterHijrah from '@/components/FooterHijrah.vue'



export default {
  name: 'Home',
  components: {
    HeaderHijrah,
    HeroHijrah,
    BannerHijrah,
    InstaHijrah,
    PartnerHijrah,
    FooterHijrah
    
  }
}
</script>
