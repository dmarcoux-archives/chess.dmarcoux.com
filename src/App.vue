<template>
  <div id="app">
    <chessboard />
  </div>
</template>

<script>
import { chessboard } from 'vue-chessboard';
import 'vue-chessboard/dist/vue-chessboard.css';

export default {
  name: 'App',
  components: {
    chessboard,
  },
};
</script>
