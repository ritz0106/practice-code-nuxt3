<template>
  <div>
    <span> I am id page {{ route.params.id }}</span>
  </div>
</template>
<script setup>
const route = useRoute()
</script>