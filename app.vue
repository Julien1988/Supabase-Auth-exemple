<script setup>
const user = useSupabaseUser();
console.log(user.value)

</script>

<template>
 <NuxtPage/>
</template>