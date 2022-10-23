<template>
  <button @click="shuffleCards()" class="start-btn">{{ text }}</button>
</template>

<script>
export default {
  name: "StartButton",
  props: {
    text: String,
    color: String,
  },
  methods: {
    onclick() {
      console.log();
    },
  },
}
</script>

<style>
.start-btn {
  position: absolute;
  top: 40px;
  color: blue;
  padding: 10px;
  font-weight: bold;
  font-size: large;
  border: 2px solid blue;}
</style>