<template>
  <div class="hello">
    <div class="input-wrapper">
      <input type="text" v-model="inputValue" v-bind:class="borderClass">
      <div v-if="inlineClass" class="inlineClass">exceeding 50 characters</div>
    </div>
    <div class="button-wrapper">
      <button v-bind:disabled="isButton">Submit</button>
    </div>
  </div>
</template>
<script src="./HelloWorld.js"></script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style src="./HelloWorld.css" scoped>

</style>