
<template>
    <!-- 组件的结构 -->
     <div class="demo">
        <h2>名称：{{schoolname}}</h2>
        <h2>地址：{{address}}</h2>
        <button @click="showName">tip name</button>

     </div>
</template>


<script>
    // 组件交互相关的代码
    export default {
        name:'School',
        data(){
            return {
                schoolname:'sname',
                address:'address'
            }
        },
        methods:{
            showName(){
                console.log(this.schoolname)
            }
        }
    }
</script>


<style>
    /* 组件的样式 */
    .demo {
        background-color: antiquewhite;
    }
</style>