
<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <h2>{{ msg }}</h2>
  <button type="button">count is: {{ count }}</button>
  <p>
    Edit
    <code>components/HelloWorld.vue</code> to test hot module replacement
  </p>
</template>

<script>
export default {
  data() {
    return {
      count: 0
    }
  }
}
</script>

<style scoped>
button {
  font-weight: bold;
  padding: 0.5rem;
  margin: 0.5rem;
  border-radius: 0.5rem;
  border: 1px solid #ccc;
  background: #f5f5f5;
  cursor: pointer;
}
button:hover {
  background: #e5e5e5;
}
</style>
