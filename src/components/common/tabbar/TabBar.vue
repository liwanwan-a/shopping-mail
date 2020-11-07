<template>
    <div id="tab-bar">
        <slot></slot>
    </div>
</template>

<script>
    export default {
        name: "TabBar"
    }
</script>

<style scoped>
    #tab-bar{
        position: fixed;
        bottom: 0px;
        height: 55px;
        left: 0px;
        right: 0px;
        display: flex;
        text-align: center;
        /*justify-content: space-around;*/
        background: #ccc;
    }

</style>