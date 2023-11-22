<script setup>
import { ref } from 'vue';


const selectedValue = ref('');

</script>

<template>
<div class="first">
         <p>SELECT YOUR</p>
        <img src="/images/pngegg (12).png" alt="" class="firstimage">

         <p>CHARACTER</p>
         <select v-model="selectedValue" class="custom-select">
            <option value="LUFFY">LUFFY</option>
            <option value="NAMI">NAMI</option>
            <option value="SANJI">SANJI</option>
            <option value="ZORO">ZORO</option>
            <option value="USOPP">USOPP</option>
            <option value="CHOPPER">CHOPPER</option>
        </select>

        <div v-if="selectedValue === 'LUFFY'">
            <div class="container">
                <img src="/images/pngegg (11).png" alt="" class="custom-image">
                <h1 class="custom-heading">LUFFY</h1>
            </div>
        </div>

        <div v-else-if="selectedValue === 'NAMI'">
            <div class="container">
                <img src="/images/pngegg (14).png" alt="" class="custom-image2">
                <h1 class="custom-heading">NAMI</h1>
            </div>
        </div>

        <div v-else-if="selectedValue === 'SANJI'">
            <div class="container">
                <img src="/images/pngegg (13).png" alt="" class="custom-image3">
                <h1 class="custom-heading">SANJI</h1>
            </div>
        </div>

        <div v-else-if="selectedValue === 'ZORO'">
            <div class="container">
                <img src="/images/pngegg (15).png" alt="" class="custom-image4">
                <h1 class="custom-heading">ZORO</h1>
            </div>
        </div>

        <div v-else-if="selectedValue === 'USOPP'">
            <div class="container">
                <img src="/images/pngegg (16).png" alt="" class="custom-image4">
                <h1 class="custom-heading">USOPP</h1>
            </div>
        </div>

        <div v-else-if="selectedValue === 'CHOPPER'">
            <div class="container">
                <img src="/images/pngegg (17).png" alt="" class="custom-image4">
                <h1 class="custom-heading">CHOPPER</h1>
            </div>
        </div>
</div>
</template>