<template>
<HeaderNav />
  <router-view />
</template>

<script>
import '@/scss/global.scss';
import HeaderNav from '@/components/HeaderNav.vue'

export default {
  components: {
    HeaderNav
  }
};
</script>


