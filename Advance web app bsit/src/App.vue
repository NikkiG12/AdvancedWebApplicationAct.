<script setup>
import { ref } from 'vue';
const input = ref('')
</script>
<template>
    <!-- two-way binding -->
    <select v-model="input">
        <option value="NS">NS</option>
        <option value="AC">AC</option>
        <option value="MM">MM</option>
        <option value="R">R</option>
    </select> 
    <h1 v-if="input == 'NS'" style="font-family: 'Pacifico', cursive; font-size: 50px;">Nike Shian</h1>
    <p v-else-if="input == 'AC'" style="font-family: 'Pacifico', cursive; font-size: 50px;">Angelo Cris</p>
    <p v-else-if="input == 'MM'" style="font-family: 'Pacifico', cursive; font-size: 50px;">Mary Mayumi</p>
    <p v-else-if="input == 'R'" style="font-family: 'Pacifico', cursive; font-size: 50px;">Riza</p>
    <p v-else style="font-family: 'Pacifico', cursive; font-size: 50px;">Others</p>
</template>

