<script setup>
//不能使用require
import Download from '@/img/home_banner_download.png'
import Jiaolian from '@/img/home_banner_jiaolian.jpg'
import Jiaxiaobang from '@/img/home_banner_jiaxiaobang.png'
import New1 from '@/img/home_banner_new1.jpeg'
const imgSrc = [
    { id: 1, src: Download, link:'https://www.jiakaobaodian.com/download' },
    { id: 2, src: Jiaolian, link: 'https://www.mucang.cn/jiaolianbaodian/?from=jxrz-topbanner' },
    { id: 3, src: Jiaxiaobang, link: 'https://saas-shop.jiakaobaodian.com/runtu/cooperate.html' },
    { id: 4, src: New1, link: 'https://www.mucang.cn/company/honor/' }
]
</script>

<template>
    <div class="banner">
        <div class="banner-content">
            <el-carousel trigger="click" height="380px">
                <el-carousel-item v-for="item in imgSrc" :key="item.id">
                    <a class="banner-img" target="_blank" :href="item.link">
                        <div class="banner-img"
                            :style="{ background: `url(${item.src}) center no-repeat`}">
                        </div>
                    </a>
                </el-carousel-item>
            </el-carousel>
        </div>
        <!-- <div class="banner-menu">

        </div> -->
    </div>
</template>

<style lang="less" scoped>
.banner {
    width: 100%;
    height: 380px;
    .banner-content{
        margin: 0 auto;
        .banner-img {
                width:  100%;
                height: 100%;
            }
    }
    .banner-menu {
        width: 280px;
        height: 335px;
        background-color: #FFFFFFE6;
    }
}
</style>
