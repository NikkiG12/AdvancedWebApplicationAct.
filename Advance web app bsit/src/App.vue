<script setup>

import BaseCondition from './components/BaseCondition.vue'
import BaseLoop from './components/BaseLoop.vue'


import { ref } from 'vue';
import './style.css';


</script>

<template>
<BaseCondition />
<BaseLoop />


</template>

<style>
.app-container {
  display: flex;
  justify-content: space-around;
  align-items: center;
  flex-wrap: wrap;
  padding: 20px;
}

/* You can add additional styling for each component if needed */
</style>