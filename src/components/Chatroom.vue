<script setup>
import { ref } from 'vue'

defineProps({
  clientUsername : String,
})

const personCount = ref(0)
</script>

<template>
  <div class="mainOuterBox">
    <div class="mainInnerBox">
      <h2>{{ personCount }} on break</h2>      
      <div class="chatBox">
        hello
      </div>
      <form>
        <p class="messageUsername">{{ clientUsername }}:</p>
        <input></input>
        <button class="messageButton">Send</button>
      </form>
    </div>
  </div>
</template>