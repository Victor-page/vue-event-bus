<template>
  <ul class="list-group">
    <server-item v-for="server in servers" :key="server.id" :server="server">
    </server-item>
  </ul>
</template>

<script>
import ServerItem from './ServerItem.vue';

export default {
  components: {
    'server-item': ServerItem,
  },
  data() {
    return {
      servers: [
        { id: 1, status: 'Normal' },
        { id: 2, status: 'Normal' },
        { id: 3, status: 'Critical' },
        { id: 4, status: 'Unknown' },
        { id: 5, status: 'Normal' },
      ],
    };
  },
};
</script>

<style></style>
