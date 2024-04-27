<template>
    <h1 class="text-red">Global styling</h1>
    <p class="local">Trying local scope in this component</p>
</template>
<!-- local style and becomes global if scoped attribute is not present in the style tag -->
<style scoped>
    .text-red{
        color: red;
    }
</style>