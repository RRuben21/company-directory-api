<script setup>
import MaincardSingle from './MaincardSingle.vue/';
import useAPI from '@/composables/useAPI';

const {employees} = useAPI()

</script>


<template>
<div class="grid grid-cols-5 gap-10 p-10">
    <MaincardSingle v-for = "employee in employees" :key="employee._id" :employee="employee"></MaincardSingle>
</div>


</template>