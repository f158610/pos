<template>
    <div class="left-nav">
        <ul>
            <li>
                <i class="icon iconfont icon-kafei"></i>
                <div>商品</div>
            </li>
            <li>
                <i class="icon iconfont icon-31dianpu"></i>
                <div>店铺</div>
            </li>
            <li>
                <i class="icon iconfont icon-gouwuchexuanzhong"></i>
                <div>收银</div>
            </li>
            <li>
                <i class="icon iconfont icon-huiyuanqia"></i>
                <div>会员</div>
            </li>
            <li>
                <i class="icon iconfont icon-gongnengjianyi"></i>
                <div>统计</div>
            </li>
        </ul>
    </div>
</template>

<script>
    export default {
        name:'leftNav',
        data() {
            return {
                
            }
        },
    }
</script>

<style scoped>
.left-nav {
    width: 5%;
    height: 100%;
    color: #ffffff;
    background: #1D8ce0;
    float: left;
    font-size: 10px;
}
.iconfont{
    font-size:24px;
}
.left-nav ul{
    list-style: none;
    margin: 0;
    padding: 0;
}
.left-nav li{
    text-align: center;
    border-bottom:1px solid #20a0ff;
    padding: 10px;
}
</style>