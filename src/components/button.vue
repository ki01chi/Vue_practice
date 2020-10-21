<template>
   <div
  class="button"
  @click="$emit('onClick', $event)"
  >
    {{ title }}
  </div>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      default: 'ボタン'
    }
  }
}
</script>

<style scoped>
  .button {
    display: inline-block;
    background-color: red;
    border-radius: 5px;
    color: white;
    padding: 10px;
    cursor: pointer;
    margin-right: 5px;
  }

  .button:hover {
   background-color: rgb(182, 0, 0); 
  }

  .button:active {
    background-color: rgb(138, 13, 13);
  }
</style>