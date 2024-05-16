<script setup>

</script>

<template>
    <div class="home-part03">
        <div class="part03-title">
            学车流程
            <p>驾考宝典整合学车全流程，驾考宝典为用户提供全方位学车服务</p>
        </div>
        <div class="part03-content">
            <div class="content-items">
                <div class="item">
                    <a href="https://www.jiakaobaodian.com/wuhan/school/">
                        <img src="@/img/part03-1.png" alt="">
                        <div class="item-title">
                            找驾校
                        </div>
                        <p>口碑好的驾校</p>
                    </a>
                </div>
                <div class="item">
                    <a href="https://www.jiakaobaodian.com/mnks/kemu1/car.html">
                        <img src="@/img/part03-2.png" alt="">
                        <div class="item-title">
                            科目一
                        </div>
                        <p>驾驶员理论考试</p>
                    </a>
                </div>
                <div class="item">
                    <a href="https://www.jiakaobaodian.com/mnks/kemu2/car.html">
                        <img src="@/img/part03-3.png" alt="">
                        <div class="item-title">
                            科目二
                        </div>
                        <p>场地驾驶技能考试科目</p>
                    </a>
                </div>
                <div class="item">
                    <a href="https://www.jiakaobaodian.com/mnks/kemu3/car.html">
                        <img src="@/img/part03-4.png" alt="">
                        <div class="item-title">
                            科目三
                        </div>
                        <p>机动车驾驶人道路考试</p>
                    </a>
                </div>
                <div class="item">
                    <a href="https://www.jiakaobaodian.com/mnks/kemu4/car.html">
                        <img src="@/img/part03-5.png" alt="">
                        <div class="item-title">
                            科目四
                        </div>
                        <p>安全文明驾驶常识考试</p>
                    </a>
                </div>
                <div class="item">
                    <a href="javascript:;">
                        <img src="@/img/part03-6.png" alt="">
                        <div class="item-title">
                            拿本
                        </div>
                        <p>开心拿本，安全驾驶</p>
                    </a>
                </div>
            </div>
        </div>
        <div class="part03-title">
            宝典荣誉
            <p>强大的驾考功能，优秀的用户体验，我们的愿景是学车无忧，轻松拿本</p>
            <img src="@/img/home-dynamic.png" alt="" style="width: 100%;height: 100%;">
        </div>
    </div>
</template>

<style lang="less" scoped>
.home-part03 {
    width: 1200px;
    margin: 0 auto;
    text-align: center;

    .part03-title {
        margin-top: 60px;
        font-size: 30px;
        color: #333333;

        p {
            font-size: 16px;
            margin: 30px 0;
            color: #666666;
        }
    }

    .part03-content {
        a {
            text-decoration: none;
        }

        .content-items {
            display: flex;

            .item {
                padding: 0px 20px 0;
                flex: 1;
                
                .item-title {
                    font-size: 24px;
                    color: #333333;
                    &:hover {
                        color: rgb(79, 190, 249);
                    }
                }

                img {
                    margin-bottom: 30px;
                    &:hover {
                            background-color: rgb(79, 190, 249);
                        }
                    &:hover ~ .item-title{
                        color:  rgb(79, 190, 249);;
                    }
                }

                p {
                    margin-top: 15px;
                    font-size: 14px;
                    color: #999999;
                }
            }
        }
    }
}
</style>
