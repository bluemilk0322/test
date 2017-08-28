<template>
  <div id="app">
    <Nav></Nav>
    <Jum></Jum>
    <Card></Card>
    <router-view></router-view>
  </div>
</template>

<script>
import Nav from '@/components/Nav'
import Jum from '@/components/Jumbotron'
import Card from '@/components/Card'

export default {
  name: 'app',
  components: {
    Nav,
    Jum,
    Card
  }
}
</script>

<style lang="scss">
@import "~bootstrap/scss/bootstrap";

</style>
