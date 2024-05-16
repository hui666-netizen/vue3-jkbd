<script setup>

</script>

<template>
    <div class="top">
        <div class="top-log">
            <a href="https://wuhan.jiakaobaodian.com/"><img src="@/img/log.png" alt=""></a>
        </div>
        <div class="top-search">
            <el-input v-model="input" placeholder="请输入关键字" />
            <el-button class="top-button">搜 索</el-button>
        </div>
    </div>
</template>

<style>
.top {
    width: 1200px;
    height: 42px;
    margin: 28px auto;
    display: flex;
    justify-content: space-between;
}

.top-search {
    width: 300px;
    height: 42px;
    display: flex;
}

.top-search .top-button {
    width: 53px;
    height: 42px;
    background-color: #F0F0F0;
}
</style>
