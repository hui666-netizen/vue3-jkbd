<script setup>
import { ref } from 'vue';
const centerDialogVisible = ref(false)
const ruleForm = ref({
    name: '',
    phone: '',
    yanze: '',
    jz: '',
    location: ''
})
const y = ref(false)
const options = ref([
    {
        value: 'c1',
        label: 'c1',
},
    {
        value: 'c2',
        label: 'c2',
    },
])
</script>

<template>
    <div class="home-part02">
        <img src="@/img/banner-jxb.png" alt="" class="part02-img">
        <div class="part02-title">
            武汉市驾校推荐
        </div>
        <div class="part02-content">
            <div class="content-items">
                <div class="content-item">
                    <div class="item-shang">
                        <div class="shang01">
                            <div class="div01">
                                <div class="jx">兰剑驾校<img src="@/img/star-5.png" alt="" class="mark"></div>
                            </div>
                            <div class="div2">
                                <div class="part">
                                    <img src="@/img/dui.png" alt="" class="part-img">
                                    <span class="part-span">口碑好</span>
                                </div>
                                <div class="part">
                                    <img src="@/img/dui.png" alt="" class="part-img">
                                    <span class="part-span">规模大</span>
                                </div>
                                <div class="part">
                                    <img src="@/img/dui.png" alt="" class="part-img">
                                    <span class="part-span">拿本快</span>
                                </div>
                                <div class="part">
                                    <img src="@/img/dui.png" alt="" class="part-img">
                                    <span class="part-span">包接送</span>
                                </div>
                            </div>
                        </div>
                        <div class="shang02">
                            ￥2680
                        </div>
                        <div class="shang03">
                            <button @click="centerDialogVisible = true">学车报名</button>
                        </div>
                    </div>
                    <div class="item-xia">
                        <img src="@/img/part02-1.jpg" alt="" class="xia-img">
                        <p class="xia-p">教练都很好 都很用心 都过啦 拿证啦</p>
                    </div>
                </div>
                <div class="content-item">
                    <div class="item-shang">
                        <div class="shang01">
                            <div class="div01">
                                <div class="jx">永安驾校<img src="@/img/star-4.5.png" alt="" class="mark"></div>
                            </div>
                            <div class="div2">
                                <div class="part"><img src="@/img/dui.png" alt="" class="part-img">
                                    <span class="part-span">
                                        口碑好
                                    </span>
                                </div>
                                <div class="part"><img src="@/img/dui.png" alt="" class="part-img">
                                    <span class="part-span">
                                        规模大
                                    </span>
                                </div>
                                <div class="part"><img src="@/img/dui.png" alt="" class="part-img">
                                    <span class="part-span">
                                        拿本快
                                    </span>
                                </div>
                                <div class="part"><img src="@/img/dui.png" alt="" class="part-img">
                                    <span class="part-span">
                                        包接送
                                    </span>
                                </div>
                            </div>
                        </div>
                        <div class="shang02">
                            ￥2680
                        </div>
                        <div class="shang03">
                            <button @click="centerDialogVisible = true">学车报名</button>
                        </div>
                    </div>
                    <div class="item-xia">
                        <img src="@/img/part02-2.jpg" alt="" class="xia-img">
                        <p class="xia-p">
                            必教练很辛苦，作为永安驾校教练，真的很辛苦，在大家放假休闲的时间却是他们最忙碌的时间。他们春夏秋冬室外作业，无论是酷暑还是严寒，他们都要面对恶劣的天气，无论放假和双休日他们都有自己的教学任务。
                        </p>
                    </div>
                </div>
                <div class="content-item">
                    <div class="item-shang">
                        <div class="shang01">
                            <div class="div01">
                                <div class="jx">德友驾校<img src="@/img/star-4.5.png" alt="" class="mark"></div>
                            </div>
                            <div class="div2">
                                <div class="part">
                                    <img src="@/img/dui.png" alt="" class="part-img">
                                    <span class="part-span">口碑好</span>
                                </div>
                                <div class="part">
                                    <img src="@/img/dui.png" alt="" class="part-img">
                                    <span class="part-span">规模大</span>
                                </div>
                                <div class="part">
                                    <img src="@/img/dui.png" alt="" class="part-img">
                                    <span class="part-span">拿本快</span>
                                </div>
                                <div class="part">
                                    <img src="@/img/dui.png" alt="" class="part-img">
                                    <span class="part-span">包接送</span>
                                </div>
                            </div>
                        </div>
                        <div class="shang02">
                            ￥2780
                        </div>
                        <div class="shang03">
                            <button @click="centerDialogVisible = true">学车报名</button>
                        </div>
                    </div>
                    <div class="item-xia">
                        <img src="@/img/part02-3.jpg" alt="" class="xia-img">
                        <p class="xia-p">首先这个驾校最便宜2500，我交2800，其次科目二要交模拟费，3月7报名到5月13只摸过一次车，报了名想退的，别签电子合同。</p>
                    </div>
                </div>
                <div class="content-item">
                    <div class="item-shang">
                        <div class="shang01">
                            <div class="div01">
                                <div class="jx">宏达驾校<img src="@/img/star-5.png" alt="" class="mark"></div>
                            </div>
                            <div class="div2">
                                <div class="part">
                                    <img src="@/img/dui.png" alt="" class="part-img">
                                    <span class="part-span">口碑好</span>
                                </div>
                                <div class="part">
                                    <img src="@/img/dui.png" alt="" class="part-img">
                                    <span class="part-span">规模大</span>
                                </div>
                                <div class="part">
                                    <img src="@/img/dui.png" alt="" class="part-img">
                                    <span class="part-span">拿本快</span>
                                </div>
                                <div class="part">
                                    <img src="@/img/dui.png" alt="" class="part-img">
                                    <span class="part-span">包接送</span>
                                </div>
                            </div>
                        </div>
                        <div class="shang02">
                            ￥2980
                        </div>
                        <div class="shang03">
                            <button @click="centerDialogVisible = true">学车报名</button>
                        </div>
                    </div>
                    <div class="item-xia">
                        <img src="@/img/part02-4.jpg" alt="" class="xia-img">
                        <p class="xia-p">驾校很规范，出地铁口走一会就到了。没有乱七八糟的收费，约课也很方便，每一位教练都很认真负责，学车过程非常愉快。</p>
                    </div>
                </div>
            </div>
        </div>
        <div class="but">
            <a href="https://www.jiakaobaodian.com/wuhan/school/"><el-button plain style="width: 280px;
            height: 50px; font-size: 16px; color: #999999;">查看更多</el-button></a>
        </div>
        <el-dialog v-model="centerDialogVisible" width="600px" align-center class="dialog">
            <p class="p1">免费咨询</p>
            <p class="p2">留下你的联系方式，不久后会受到来电</p>
            <el-form ref="ruleFormRef" style="width: 500px; margin: 0 auto;" :model="ruleForm" status-icon
                :rules="rules" label-width="auto" class="Form">
                <el-form-item label="姓名" prop="name">
                    <el-input v-model="ruleForm.name" autocomplete="off" size="large" />
                </el-form-item>
                <el-form-item label="手机" prop="phone">
                    <el-input v-model="ruleForm.phone" autocomplete="off" size="large" />
                </el-form-item>
                <el-form-item label="验证" prop="yanze">
                    <div class="yz">
                        <el-input v-model="ruleForm.yanze" style="width: 340px;" autocomplete="off" size="large" />
                        <el-button type="primary" style="width: 120px;" size="large">短信验证码</el-button>
                    </div>
                </el-form-item>
                <el-form-item label="驾照" prop="jz">
                    <el-select v-model="value" placeholder="c1" size="large">
                        <el-option v-for="item in options" :key="item.value" :label="item.label" :value="item.value" />
                    </el-select>
                </el-form-item>
                <el-form-item label="位置" prop="location">
                    <el-input v-model="ruleForm.location" autocomplete="off" size="large" />
                </el-form-item>
                <div class="submit">
                    <el-button type="primary" size="large">提交</el-button>
                </div>
                <div class="y">
                    <el-checkbox v-model="y">同意《隐私政策》和《个人信息保护声明》</el-checkbox>
                </div>

            </el-form>
        </el-dialog>
    </div>
</template>

<style lang="less" scoped>
.home-part02 {
    width: 1260px;
    margin: 0 auto;

    .dialog {
        padding: 40px;
        .y{
            text-align: center;
        }
        .submit{
            width: 100%;
            text-align: center;
            button{
                width: 80%;
            }
            
        }
        .yz{
            display: flex;
            flex-wrap: nowrap;
        }
        .p1 {
            text-align: center;
            padding: 10px;
            font-size: 20px;
            color: #333333;
        }

        .p2 {
            text-align: center;
            padding: 0 0 20px 20px;
            font-size: 14px;
            color: #999999;
        }
    }

    .part02-img {
        margin-top: 40px;
        margin-bottom: 60px;
        width: 100%;
        height: 100%;
    }

    .part02-title {
        margin-bottom: 40px;
        font-size: 30px;
        color: #333333;
        text-align: center;
        height: 40px;
        line-height: 40px;
    }

    .content-items {
        display: flex;
        flex-wrap: wrap;

        .content-item {
            flex: 1;
            border: 1px solid #e9e9e9;
            margin: 0 30px 30px 0;
            padding: 40px 30px;

            .item-shang {
                display: flex;
            }

            .div01 {
                width: 305px;

                .jx {
                    font-size: 22px;
                    color: #666666;

                    img {
                        margin-left: 10px;
                    }
                }
            }

            .div2 {
                display: flex;
                align-items: center;
                height: 17px;
                margin-top: 10px;

                .part {
                    margin-right: 10px;

                    img {
                        margin-right: 5px;
                        position: relative;
                        top: 3px
                    }
                }
            }
        }

        .shang02 {
            color: #EE4653;
            font-size: 30px;
            height: 63px;
            line-height: 63px;
            padding: 0 20px;
            border-left: 1px solid #e9e9e9;
        }

        .shang03 {
            button {
                cursor: pointer;
                width: 80px;
                line-height: 28px;
                background: 0 0;
                font-size: 14px;
                margin-top: 17px;
                border: 1px solid #e9e9e9;
            }
        }

        .item-xia {
            display: flex;
            margin-top: 30px;
            padding: 20px;
            background-color: #FAFAFA;

            img {
                width: 40px;
                height: 40px;
                margin-right: 20px;
            }

            p {
                height: 40px;
                padding-top: 5px;
                font-size: 14px;
                color: #999999;
                overflow: hidden;
                text-overflow: ellipsis;
            }
        }
    }

    .but {
        margin-top: 20px;
        text-align: center;
        color: #999999;
        font-size: 16px;
    }
}
</style>
