<template>
    <div id="comfirm">
        <div>{{ msg }}</div>
        <button @click="getButton">{{text}}</button>
    </div>
</template>
<script>
export default {
    name:"comfirm",
    props:["text"],
    data() {
        return {
            msg:'say hello'
        }
    },
    methods: {
        getButton(){
            this.$emit('message',this.msg)  //点击传值给父组件
        },
    },
}
</script>