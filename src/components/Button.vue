<template>
  <button v-bind:type="type" v-bind:class="className" :disabled="disabled">{{text}}</button>
</template>

<script>
export default {
    props: {
        text: String,
        type: String,
        className: String,
        disabled: Boolean,

    },
    inheritAttrs: false,
}
</script>

<style>
.red{
    background-color:rgb(189, 0, 38);
    color: white;
}

.blue{
    background-color: rgb(70, 156, 253);
}

.green{
    background-color:rgba(0, 211, 0, 0.849);
}

.yellow{
    background-color:rgba(216, 216, 65, 0.924);
}

.button{
    border-radius: 5px;
    margin: 6px;
    padding: 2px 10px; /* top-bottom, left-right */
}

.purple{
    background-color: rgb(149, 20, 255);
    color: white;
}

</style>
