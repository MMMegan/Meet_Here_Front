<template>
  <div>
      <h3>Counter.vue</h3>
    {{ count }}
    <button @click="increment">自增</button>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        count: 0
      }
    },

    methods: {
      increment() {
        this.count++
      }
    }
  }
</script>