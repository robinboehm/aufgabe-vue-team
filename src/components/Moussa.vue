<template>
  <h1>Hello there!</h1>
  <button @click="OnClick">Hallo</button>
</template>

<script>
export default {
  name: "Moussa",

  data() {
    return {
      hallo: "Hallo zusammen",
    };
  },

  methods: {
    OnClick() {
      console.log(this.hallo);
    },
  },
};
</script>
