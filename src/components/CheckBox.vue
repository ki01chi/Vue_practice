<template>
<div>

    <input 
    id="checkbox"
    type="checkbox"
    v-model="checked"
    >
    <label for="checkbox">チェック</label>
    <p>チェック値：{{ checked }}</p>

</div>
</template>

<script>
export default {
  data() {
    return {
      checked: false
    }
  }
}
</script>

<style>

</style>