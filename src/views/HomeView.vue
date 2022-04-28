<template>
  <div class="home">
    <HeaderSyahna />
    <HeroSyahna />
    <BannerSyahna />
    <InstaSyahna />
    <PartnerSyahna />
    <FooterSyahna />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue';
import HeaderSyahna from '@/components/HeaderSyahna.vue';
import HeroSyahna from '@/components/HeroSyahna.vue';
import BannerSyahna from '@/components/BannerSyahna.vue';
import InstaSyahna from '@/components/InstaSyahna.vue';
import PartnerSyahna from '@/components/PartnerSyahna.vue';
import FooterSyahna from '@/components/FooterSyahna.vue';

export default {
  name: 'HomeView',
  components: {
    HeaderSyahna,
    HeroSyahna,
    BannerSyahna,
    InstaSyahna,
    PartnerSyahna,
    FooterSyahna
  }
};
</script>
