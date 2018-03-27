<template>
  <div>
    <h1> {{ title }} </h1>
    <p> {{ greeting() }} </p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      title: 'first Vue file!'
    }
  },
  methods: {
    greeting: function() {
      return 'hello';
    }
  }
}
</script>

<style>
</style>
