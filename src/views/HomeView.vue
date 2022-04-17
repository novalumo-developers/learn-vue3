<script setup lang="ts"></script>
<script lang="ts">
export default {
  name: "HomeView",
  data() {
    return {
      message: "Hello Vue!",
      count: 0,
    };
  },
  methods: {
    increment() {
      this.count++;
    },
  },
  mounted() {
    alert("mounted");
  },
};
</script>

<template>
  <main>
    {{ message }}
    {{ count }}
    <button @click="increment">Increment</button>
  </main>
</template>
