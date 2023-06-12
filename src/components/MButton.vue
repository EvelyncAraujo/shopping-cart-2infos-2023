<script setup>
const props = defineProps({
    text: String
})
</script>

<template>

<button>{{props.text}}</button>

</template>

<style scoped>
button{
    background-color: rgb(117, 80, 80);
    color: white;
    border: none;
    border-radius: 3px;
    padding: 4px;
    font-size: 1rem;
    cursor: pointer;
    margin: 3px;
}
button:hover{
    background-color: rgb(61, 60, 60);
}
</style>