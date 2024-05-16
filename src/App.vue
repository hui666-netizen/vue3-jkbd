<script setup>
import Top from '@/components/top.vue'
import Nav from '@/components/nav.vue'
import Banner from '@/components/banner.vue'
</script>

<template>
  <div class="box">
    <Top></Top>
    <Nav></Nav>
    <Banner></Banner>
  </div>
</template>

<style>
.box{
  display: flex;
  flex-direction: column;
}
</style>
