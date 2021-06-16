<template>
  <h2>{{ msg }}</h2>
  <button @click="msg = 'Jan'">Click Me</button>
</template>

<script>
export default {
  name: "Greet",
  data() {
    return {
      msg: "Hello",
    };
  },
};
</script>
