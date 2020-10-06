<template>
  <input v-bind:placeholder="placeholder"/>
</template>

<script>
export default {
    props: {
        placeholder: String,
    }
}
</script>

<style>
input{
    
    width: 100%;
}

</style>