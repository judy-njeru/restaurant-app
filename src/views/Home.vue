<template>
  <div class="home">
    <b-container class="bv-example-row">
      <b-row>
        <b-col sm="8">
          <Carousel />
        </b-col>
        <b-col sm="4">
          <OrderFlowBox class="order-flow-box"/>
        </b-col>
      </b-row>
    </b-container>
    <!-- <HelloWorld /> -->
  </div>
</template>

<script>
// @ is an alias to /src
import Carousel from '@/components/Carousel.vue'
import OrderFlowBox from '@/components/OrderFlowBox.vue'

export default {
  name: 'home',
  components: {
    Carousel,
    OrderFlowBox
  }
}
</script>

<style lang="scss">
  div.order-flow-box {
    height: 100%;
  }
</style>

