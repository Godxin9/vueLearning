
<template>
    <div>
        <h1>这是一个myButton组件</h1>
        <button @click="msg++">点击次数：{{msg}}</button>
    </div>
</template>

<script>
export default {
    data() {
        return {
            msg:0,
        }
    },
    methods:{
        click(){
            this.msg+=1
        }
    }
}
</script>

<style scoped>
    h1{
        color: hotpink;
    }
</style>