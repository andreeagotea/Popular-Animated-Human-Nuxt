<template>
  <div class="page-container"
    ><div class="page-navbar1"><app-navbar5></app-navbar5></div
    ><div class="page-hero2"
      ><app-hero8
        heading1="Engaging and attention-grabbing hero headline that leaves a lasting impression"
      ></app-hero8></div
    ><div class="page-stats3"><app-stats2></app-stats2></div
    ><div class="page-logos4"><app-logos1></app-logos1></div
    ><div class="page-features5"><app-features1></app-features1></div
    ><div class="page-team6"><app-team1></app-team1></div
    ><div class="page-footer7"><app-footer1></app-footer1></div
  ></div>
</template>

<script>
import AppNavbar5 from '../components/navbar5'
import AppHero8 from '../components/hero8'
import AppStats2 from '../components/stats2'
import AppLogos1 from '../components/logos1'
import AppFeatures1 from '../components/features1'
import AppTeam1 from '../components/team1'
import AppFooter1 from '../components/footer1'

export default {
  name: 'Page',
  props: {},
  components: {
    AppNavbar5,
    AppHero8,
    AppStats2,
    AppLogos1,
    AppFeatures1,
    AppTeam1,
    AppFooter1,
  },
  head: {
    title: 'Page - Popular Animated Human',
    meta: [
      {
        property: 'og:title',
        content: 'Page - Popular Animated Human',
      },
    ],
  },
}
</script>

<style scoped>
.page-container {
  width: 100%;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
}
.page-navbar1 {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  align-items: center;
  justify-content: center;
}
.page-hero2 {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  align-items: center;
  justify-content: center;
}
.page-stats3 {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  align-items: center;
  justify-content: center;
}
.page-logos4 {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  align-items: center;
  justify-content: center;
}
.page-features5 {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  align-items: center;
  justify-content: center;
}
.page-team6 {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  align-items: center;
  justify-content: center;
}
.page-footer7 {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>
