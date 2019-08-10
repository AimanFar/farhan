<template>

  <div class="body has-text-black has-text-weight-light">
    <Nav/>
    <slot/>
    <Footer/>
  </div>
</template>

<static-query>
query {
  metaData {
    siteName
  }
}
</static-query>

<script>
import Nav from '~/components/Nav.vue'
import Footer from '~/components/Footer.vue'

export default {
  components: {
    Nav, Footer
  }  
}
</script>


<style>
.body {
  font-family: 'Jost';
  font-weight: 400;
  font-size: 1.1rem;
}
.title {
  color: #020202;
}
</style>
