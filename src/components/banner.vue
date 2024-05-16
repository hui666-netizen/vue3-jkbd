<script setup>
//不能使用require
import Download from '@/img/home_banner_download.png'
import Jiaolian from '@/img/home_banner_jiaolian.jpg'
import Jiaxiaobang from '@/img/home_banner_jiaxiaobang.png'
import New1 from '@/img/home_banner_new1.jpeg'
const imgSrc = [
    { id: 1, src: Download, link: 'https://www.jiakaobaodian.com/download' },
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
                        <div class="banner-img" :style="{ background: `url(${item.src}) center no-repeat` }">
                        </div>
                    </a>
                </el-carousel-item>
            </el-carousel>
        </div>
        <div class="banner-menu-re">
            <div class="banner-menu">
                <div class="banner-menu-title">
                    学车流程
                </div>
                <div class="banner-menu-items">
                    <div class="banner-menu-item">
                        <div class="item-icon"><img src="@/img/menu01.png" alt=""></div>
                        <div class="item-content">
                            <a href="https://www.jiakaobaodian.com/mnks/kemu1/car-wuhan.html">
                                <p class="shang">科目一</p>
                            </a>
                            <p class="xia">2024年新题库</p>
                        </div>
                    </div>
                    <div class="banner-menu-item">
                        <div class="item-icon"><img src="@/img/menu02.png" alt=""></div>
                        <div class="item-content">
                            <a href="https://www.jiakaobaodian.com/mnks/kemu2/car-wuhan.html">
                                <p class="shang">科目二</p>
                            </a>
                            <p class="xia">精选视频，详讲考点</p>
                        </div>
                    </div>
                    <div class="banner-menu-item">
                        <div class="item-icon"><img src="@/img/menu03.png" alt=""></div>
                        <div class="item-content">
                            <a href="https://www.jiakaobaodian.com/mnks/kemu3/car-wuhan.html">
                                <p class="shang">科目三</p>
                            </a>
                            <p class="xia">全方位讲解，攻克难点</p>
                        </div>
                    </div>
                    <div class="banner-menu-item">
                        <div class="item-icon"><img src="@/img/menu04.png" alt=""></div>
                        <div class="item-content">
                            <a href="https://www.jiakaobaodian.com/mnks/kemu4/car-wuhan.html">
                                <p class="shang">科目四</p>
                            </a>
                            <p class="xia">2024年新题库</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="less" scoped>
.banner {
    width: 100%;
    height: 380px;
        position: relative;
    .banner-content {
        margin: 0 auto;
        
        .banner-img {
            width: 100%;
            height: 100%;
        }
    }
.banner-menu-re{
    width: 1200px;
    margin: 0 auto;
    position: relative;

    .banner-menu {
        position: absolute;
        top: -358px;
        left: 0px;
        width: 240px;
        padding: 0 20px;
        background-color: #FFFFFFE6;

        .banner-menu-title {
            text-align: center;
            font-size: 20px;
            height: 50px;
            line-height: 50px;
        }

        .banner-menu-item {
            padding: 10px 20px 18px 0px;
            display: flex;
            flex-wrap: nowrap;

            a {
                text-decoration: none;
            }

            img {
                padding-right: 20px;
            }

            p {
                margin-top: 5px;
            }

            .shang {
                font-size: 16px;
                color: #37B5F8;
            }

            .xia {
                font-size: 14px;
                color: #666666;
            }
        }
    }
}
}
</style>
