<template>
    <div>
        <div class="h">头部</div>
        <div>
            <router-link to="/list">Go to List</router-link>
            <!-- 留坑，非常重要 -->
            <router-view class="b"></router-view>
                
        </div>
        <div class="f">底部</div>
    </div>
</template>
<script>
    export default {
        data(){
            return {

            }
        }
    }
</script>
<style scoped>
    .h{
        height: 100px;
        background-color: yellowgreen;
    }
    .b{
        height: 100px;
        background-color: skyblue;
    }
    .f{
        height: 100px;
        background-color: hotpink;
    }
</style>