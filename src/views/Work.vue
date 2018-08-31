<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <PortfolioList title-text="These will be portfolio items"/>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import PortfolioList from '@/components/PortfolioList.vue';

@Component({
  components: {
    PortfolioList,
  },
})
export default class Work extends Vue {}
</script>
