<template>
<p>{{ test }}</p>
</template>

<script>
export default {
  name: 'Test',
  data: function () {
    return {
      test: 'hello world! I am a test'
    }
  }
}
</script>

<style scoped>
p {
  font-size: 26px;
}
</style>
