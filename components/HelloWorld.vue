<template>
  <div>
    <h1>{{ message }}</h1>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: 'Welcome to my portfolio!',
    };
  },
};
</script>

<style scoped>
h1 {
  color: #333;
}
</style>
