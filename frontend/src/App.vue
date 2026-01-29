<script setup>
import Chatroom from './components/Chatroom.vue'
import Join from './components/Join.vue';


</script>

<template>
  <body>
    <nav>
      <h1>breakroom</h1>
      <h2>a single chatroom</h2>
    </nav>
    <div class="pageContent">
      <Chatroom client-username="abelureste" /> <!-- -->
      <!-- <Join /> -->
    </div>
  </body>
</template>