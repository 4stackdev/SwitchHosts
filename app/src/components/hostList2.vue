<template>
    <div>
        <div>this is template body</div>
        <div>{msg}</div>
    </div>
</template>

<style lang="less">
    body {
        background-color: #ff0000;
    }
</style>

<script>
    export default {
        data() {
            return {
                msg: 'hello vue'
            }
        },
        components: {}
    }
</script>
