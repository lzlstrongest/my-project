<!--  -->
<template>
  <div>demo111112233344447779999</div>
</template>

<script setup>
  import { reactive, ref, watch, onMounted, onBeforeMount } from 'vue';
  console.log('1-开始创建组件-setup');
  const refData = ref();
  onBeforeMount(() => {
    console.log('2.组件挂载页面之前执行----onBeforeMount');
  });
  onMounted(() => {
    console.log('3.-组件挂载到页面之后执行-------onMounted');
  });
</script>
<style lang="scss" scoped></style>
