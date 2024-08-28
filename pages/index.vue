<template>
  <div>
    Hello from index
    <Button @click="click">Click me</Button>
  </div>
</template>

<script lang="ts" setup>
const click = () => {
  alert("Click")
}
</script>

<style>

</style>