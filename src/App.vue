<template>
  <div>
    <TitleComponent></TitleComponent>
    <PageHero></PageHero>
  </div>
</template>

<script>
import TitleComponent from './components/TitleComponent.vue'
import PageHero from './components/PageHero.vue'

export default {
  components: {
    TitleComponent,
    PageHero,
  }
}
</script>