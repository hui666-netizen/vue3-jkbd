<script setup>

</script>

<template>
    <div class="nav">
        <ul class="nav-ul">
            <a class="first-child" href="https://wuhan.jiakaobaodian.com/">首页</a>
            <div class="dropdown">
                <a href="https://www.jiakaobaodian.com/wuhan/" class="dropbtn">模拟考试<div class="nav-icon">></div></a>
                <div class="dropdown-content">
                    <a href="https://www.jiakaobaodian.com/mnks/kemu1/car-wuhan.html">科目一</a>
                    <a href="https://www.jiakaobaodian.com/mnks/kemu2/car-wuhan.html">科目二</a>
                    <a href="https://www.jiakaobaodian.com/mnks/kemu3/car-wuhan.html">科目三</a>
                    <a href="https://www.jiakaobaodian.com/mnks/kemu4/car-wuhan.html">科目四</a>
                </div>
            </div>
            <div class="dropdown">
                <a href="https://www.jiakaobaodian.com/wuhan/school/" class="dropbtn">找驾校<div class="nav-icon">></div>
                </a>
                <div class="dropdown-content">
                    <a href="https://www.jiakaobaodian.com/wuhan/school/">找驾校</a>
                    <a href="https://www.jiakaobaodian.com/wuhan/coach/">找教练</a>
                    <a href="https://www.jiakaobaodian.com/wuhan/peilian/">找陪练</a>
                </div>
            </div>
            <a href="https://www.jiakaobaodian.com/bbs/">驾考圈</a>
            <a href="https://www.jiakaobaodian.com/sign/">交通标志</a>
            <a href="https://www.jiakaobaodian.com/download/">软件下载</a>
            <a href="https://qiye.jiakaobaodian.com/">驾考宝典企业版</a>
            <a href="https://www.futurephantom.cn/">智慧驾校</a>
            <div class="dropdown">
                <a href="https://www.maiche.com/rank/?from=jiakao_web" class="dropbtn">买新车<div class="nav-icon">></div>
                </a>
                <div class="dropdown-content">
                    <a href="https://www.maiche.com/rank/?from=jiakao_web">买车网</a>
                    <a href="https://www.pingxing.cn/">平行之家</a>
                </div>
            </div>
            <a href="https://www.xiaozhu2.com/?from=jiakao_web">二手车</a>
        </ul>
    </div>
</template>

<style lang="less" scoped>
.nav {
    width: 100%;
    height: 50px;
    background: #37B5F8;

    .nav-ul {
        margin: 0 auto;
        width: 1200px;
        height: 100%;
        font-size: 16px;
        display: flex;
        align-items: center;
        justify-content: center;
        list-style: none;
        position: relative;

        .dropbtn {
            color: white;
            padding: 16px;
            font-size: 16px;
            border: none;
            cursor: pointer;
        }

        .dropdown {
            position: relative;
            display: inline-block;
        }

        .dropdown-content {
            text-align: center;
            display: none;
            position: absolute;
            background-color: #f9f9f9;
            width: 100%;
            box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
            z-index: 1;
        }

        .dropdown-content a {
            font-size: 14px;
            color: rgb(102, 102, 102);
            padding: 12px 16px;
            text-decoration: none;
            display: block;
        }

        .dropdown:hover .dropdown-content {
            display: block;
        }

        .nav-icon {
            transform: rotate(90deg);
            background-color: transparent;
            margin-left: 3px;
            padding-top: 2px;
        }

        a {
            flex: 1;
            height: 100%;
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            color: #ffffff;
            text-decoration: none;

            &:hover {
                background-color: rgb(84, 192, 249);
            }
        }

        .first-child {
            background-color: #258Fc7;
        }

        :nth-child(7) {
            padding: 0 20px;
        }
    }
}
</style>