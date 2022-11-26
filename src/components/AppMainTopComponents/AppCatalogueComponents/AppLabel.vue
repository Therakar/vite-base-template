<script>
    export default {
        name: 'AppLabel'
    }
</script>

<template>
    <div class="label">
        <h2>CURRENT SERIES</h2>
    </div>
</template>

<style lang="scss" scoped>
    .label{
        width: 15.625rem;
        height: 50px;
        background-color: var(--primary-color);
        position: absolute;
        text-align: center;
        line-height: 50px;
        top: -25px;
    }

</style>