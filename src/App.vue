<template>
  <div class="container">
    <div class="row">
      <div class="col-xs-12">
        <vue-header> </vue-header>
      </div>
    </div>
    <hr />
    <vue-main></vue-main>
    <hr />
    <div class="row">
      <div class="col-xs-12">
        <vue-footer></vue-footer>
      </div>
    </div>
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Footer from './components/Footer.vue';
import Main from './components/Main/Main.vue';

export default {
  components: {
    'vue-header': Header,
    'vue-footer': Footer,
    'vue-main': Main,
  },
};
</script>

<style></style>
