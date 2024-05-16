<script setup>

</script>

<template>
    <div class="home-part01">
        <div class="part01-title">
            武汉2024小车理论考试
        </div>
        <div class="part01-content-items">
            <div class="part01-content-item left40">
                <div class="item-title">
                    <div class="title-icon"><img src="@/img/01.png" alt=""></div>
                    <div class="title-content">科目一交规</div>
                </div>
                <div class="item-parts">
                    <div class="item-part">
                        <div class="part-icon">
                            <img src="@/img/02.png" alt="">
                        </div>
                        <div class="part-content">
                            <div class="shang">顺序练习</div>
                            <div class="xia">按照顺序做题练习</div>
                        </div>
                    </div>
                    <div class="item-part">
                        <div class="part-icon">
                            <img src="@/img/03.png" alt="">
                        </div>
                        <div class="part-content">
                            <div class="shang">随机练习</div>
                            <div class="xia">按随机顺序做题练习</div>
                        </div>
                    </div>
                    <div class="item-part">
                        <div class="part-icon">
                            <img src="@/img/04.png" alt="">
                        </div>
                        <div class="part-content">
                            <div class="shang">专项训练</div>
                            <div class="xia">分门别类重点突破</div>
                        </div>
                    </div>
                    <div class="item-part">
                        <div class="part-icon">
                            <img src="@/img/05.png" alt="">
                        </div>
                        <div class="part-content">
                            <div class="shang">难题攻克</div>
                            <div class="xia">准确把握考试难点</div>
                        </div>
                    </div>
                </div>
                <div class="part-button"><el-button type="primary" class="but">模拟考试</el-button></div>

            </div>
            <div class="part01-content-item">
                <div class="item-title">
                    <div class="title-icon"><img src="@/img/01.png" alt=""></div>
                    <div class="title-content">科目四安全文明驾驶</div>
                </div>
                <div class="item-parts">
                    <div class="item-part">
                        <div class="part-icon">
                            <img src="@/img/02.png" alt="">
                        </div>
                        <div class="part-content">
                            <div class="shang">顺序练习</div>
                            <div class="xia">按照顺序做题练习</div>
                        </div>
                    </div>
                    <div class="item-part">
                        <div class="part-icon">
                            <img src="@/img/03.png" alt="">
                        </div>
                        <div class="part-content">
                            <div class="shang">随机练习</div>
                            <div class="xia">按随机顺序做题练习</div>
                        </div>
                    </div>
                    <div class="item-part">
                        <div class="part-icon">
                            <img src="@/img/04.png" alt="">
                        </div>
                        <div class="part-content">
                            <div class="shang">专项训练</div>
                            <div class="xia">分门别类重点突破</div>
                        </div>
                    </div>
                    <div class="item-part">
                        <div class="part-icon">
                            <img src="@/img/05.png" alt="">
                        </div>
                        <div class="part-content">
                            <div class="shang">难题攻克</div>
                            <div class="xia">准确把握考试难点</div>
                        </div>
                    </div>
                </div>
                <div class="part-button"><el-button type="primary" class="but">模拟考试</el-button></div>
            </div>

        </div>

    </div>
</template>

<style lang="less" scoped>
.left40{
    margin-right: 40px;
}
.home-part01 {
    width: 1200px;
    
    margin: 0 auto;

    .part01-title {
        text-align: center;
        color: rgb(51, 51, 51);
        font-size: 30px;
        height: 80px;
        line-height: 80px;
        margin-top: 40px;
        margin-bottom: 20px;
    }

    .part01-content-items {
        display: flex;

        

        .part01-content-item {
            width: 580px;
            border: 1px solid #e9e9e9;

            .item-title {
                height: 110px;
                display: flex;
                font-size: 20px;
                justify-content: center;
                align-items: center;
                margin: 0;

                .title-icon {
                    margin: 0;
                    padding-right: 10px;

                    img {
                        margin: 0;
                    }
                }
            }
            .item-parts{
                
                display: flex;
                flex-wrap: wrap;
                .item-part {
                        display: flex;
                        align-items: center;
                        justify-content: center;
                        width: 250px;
                        height: 70px;
                        margin: 0 0 15px 25px;
                        background-color: #FAFAFA;
                        .part-icon{
                            margin: 0;
                            padding-right: 10px;
                            
                        }
                        img{
                            margin: 0;
                        }
                    }
                    .shang{
                        font-size: 16px;
                        margin-bottom: 5px;
                        color: #333333;
                    }
                    .xia{
                        font-size: 14px;
                        color: #999999;
                    }
            }
            
        }

    }
    .part-button{
        
        margin: 20px auto;
        text-align: center;
.but{
    background-color: #37B5F8;
        min-width: 300px;
        min-height: 46px;
        font-size: 18px;
        margin-right: 0;
    }
    }
    
}
</style>
