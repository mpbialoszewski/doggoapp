<script setup>
import { ref } from 'vue'
import Rotator from './Rotator.vue';

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>


  <p>
    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Alias, voluptates. Placeat, quae saepe perspiciatis similique magnam suscipit recusandae perferendis dicta, asperiores animi aut velit repudiandae consectetur earum unde hic est!
  </p>
  <p class="read-the-docs">Click on the Vite and Vue logos to learn more</p>
  <p>
    {{ Rotator }}
  </p>

</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
