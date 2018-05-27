<template>
    <div class="box">
        <p>
            <slot></slot>
        </p>
    </div>
</template>

<script>
    export default {
        name: "message"
    }
</script>

<style scoped>
    .box{
        color: aquamarine;
    }

</style>