<template>
  <div class="row">
    <div class="col-xs-12 col-sm-6">
      <servers-list-group></servers-list-group>
    </div>
    <div class="col-xs-12 col-sm-6">
      <server-details></server-details>
    </div>
  </div>
</template>

<script>
import ServersListGroup from './ServersListGroup/ServersListGroup.vue';
import ServerDetails from './ServerDetails/ServerDetails.vue';

export default {
  components: {
    'server-details': ServerDetails,
    'servers-list-group': ServersListGroup,
  },
};
</script>

<style></style>
