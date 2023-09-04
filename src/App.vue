<script setup lang="ts">
import { ref } from 'vue';

const value1 = ref(new Date())
</script>

<template>
  <el-button type="primary">Click me</el-button>
  <el-date-picker v-model="value1" type="date" placeholder="选择日期">
  </el-date-picker>
</template>

<style scoped></style>
