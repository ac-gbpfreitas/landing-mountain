<template>
  <HeaderComponent />
  <MainContent />
  <FooterComponent />
</template>

<script>
import FooterComponent from './components/FooterComponent.vue';
import HeaderComponent from './components/HeaderComponent.vue';
import MainContent from './components/MainContent.vue';



export default {
  name: 'App',
  components: {
    HeaderComponent,
    MainContent,
    FooterComponent
  }
}
</script>

<style lang="scss" scoped></style>
