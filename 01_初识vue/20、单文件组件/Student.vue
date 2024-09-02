
<template>
    <!-- 组件的结构 -->
     <div class="demo">
        <h2>名字：{{studentname}}</h2>
        <h2>年龄：{{age}}</h2>
        

     </div>
</template>


<script>
    // 组件交互相关的代码
    export default {
        name:'student',
        data(){
            return {
                studentname:'stname',
                age: 21
            }
        },
       
    }
</script>


<style>
    /* 组件的样式 */
   
</style>