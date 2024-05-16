<script setup>

</script>

<template>
    <div class="home-part04">
        <div class="items">
            <div class="item item1">
                <span>教练宝典APP</span>
                <img src="@/img/part04-1.png" alt="">
                <img src="@/img/ma1.png" style="width: 140px;height: 140px;" alt="" class="disimg1">
            </div>
            <div class="item item2">
                <span>驾考宝典APP</span>
                <img src="@/img/part04-2.png" alt="">
                <img src="@/img/ma1.png" style="width: 140px;height: 140px;" alt="" class="disimg2">
            </div>
            <div class="item item3">
                <span>买车宝典APP</span>
                <img src="@/img/part04-3.png" alt="">
                <img src="@/img/ma3.png" style="width: 140px;height: 140px;" alt="" class="disimg3">
            </div>
        </div>
    </div>
    <div class="mas">
        <div class="boxs">
            <div class="box border">
                <div class="content">
                    <p>驾考宝典APP下载</p>
                    <span>考驾照 用宝典</span>
                </div>
                <img src="@/img/ma1.png" alt="">
            </div>
            <div class="box">
                <div class="content">
                    <p>驾考宝典微信小程序</p>
                    <span>无需下载，驾考做题更方便！</span>
                </div>
                <img src="@/img/ma2.jpg" alt="">
            </div>
        </div>
    </div>
</template>

<style lang="less" scoped>
.home-part04 {
    background-color: #f5f5f5;
    .disimg1 {
        display: none;
        z-index: 10;
        position: absolute;
        top: 180px;
        left: 120px;
    }

    .disimg2 {
        display: none;
            z-index: 10;
            position: absolute;
            top: 250px;
            left: 175px;
    }

    .disimg3 {
        display: none;
            z-index: 10;
            position: absolute;
            top: 160px;
            left: 100px;

    }

    .items {
        width: 1200px;
        height: 560px;
        margin: 0 auto;

        overflow: hidden;
        display: flex;

        .item {
            transition: all 1s ease;
            text-align: center;

            span {

                font-size: 20px;
                color: #333333;
            }

            img {
                margin-top: 20px;
            }
        }

        .item1 {
            position: relative;
            top: 100px;
            &:hover {
                top: 50px;
                opacity: 0.5;
            }

            &:hover .disimg1 {
                display: block;
                opacity: 1;
            }
        }

        .item2 {
            position: relative;
            top: 60px;

            &:hover {
                top: 10px;
                opacity: 0.5;
            }
                        &:hover .disimg2 {
                            display: block;
                        }
        }

        .item3 {
            position: relative;
            top: 150px;

            &:hover {
                top: 100px;
                opacity: 0.5;
            }
                        &:hover .disimg3 {
                            display: block;
                        }
        }
    }
}

.mas {
    width: 1200px;
    margin: 0 auto;
    display: flex;

    .boxs {
        display: flex;

        .box {
            margin: 80px 0;
            align-items: center;
            justify-content: space-between;
            display: flex;
            flex-direction: row;
            width: 440px;
            padding: 40px 80px;

            img {
                width: 140px;
                height: 140px;
            }
        }

        .border {
            border-right: 1px solid #e9e9e9;
        }
    }
}
</style>