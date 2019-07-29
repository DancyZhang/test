<template>
    <div id="home">
       <span>{{ msg }}</span> 
       comfirm
    </div>
</template>

<script>
export default {
    name:'home',
    data() {
        return {
            msg:'开始我们的vue项目'
        }
    },
}
</script>
<style lang="scss" type="text/css" scoped>
    span{
        font-size:30px;
        color: aquamarine;
    }
</style>
