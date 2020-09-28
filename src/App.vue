<template>
  <div id="app">
    <chessboard />
  </div>
</template>

<script>
import { chessboard } from 'vue-chessboard';

export default {
  name: 'App',
  components: {
    chessboard,
  },
};
</script>
