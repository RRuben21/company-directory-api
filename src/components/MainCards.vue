<script setup>
import MaincardSingle from './MaincardSingle.vue/';
</script>


<template>
<div class="grid grid-cols-5 gap-10 p-10">
    <MaincardSingle v-for = "card in 20" :key="card"></MaincardSingle>
</div>


</template>