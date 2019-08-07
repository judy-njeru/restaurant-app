<template>
  <div class="home">
    <b-container class="bv-example-row">
      <b-row>
        <b-col sm="8">
          <Carousel />
        </b-col>
        <b-col sm="4">col-sm-4</b-col>
      </b-row>
    </b-container>
    <!-- <HelloWorld /> -->
  </div>
</template>

<script>
// @ is an alias to /src
import Carousel from '@/components/Carousel.vue'

export default {
  name: 'home',
  components: {
    Carousel
  }
}
</script>
