<template>
  <input v-bind:placeholder="placeholder"/>
  <br/><br/>
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
    height: 2rem;
    font-size: 1.2rem;
    width: 100%;
    border-radius: 5px;
}

</style>