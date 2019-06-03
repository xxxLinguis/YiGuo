<template>
    <div class="mine">
        <div class="header">
            <div class="headerImg"></div>
            <i class="setting"></i>
        </div>
        <div class="account">
            <p class="list">
                <span class="num">-</span>
                <span class="txt">卡包余额</span>
            </p>
            <p class="list">
                <span class="num">-</span>
                <span class="txt">悠币</span>
            </p>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
    .header{
        height: 1.35rem;
        position: relative;
        width: 100%;
        background: #2dd282 url("http://img06.yiguoimg.com/d/web/180517/01262/143351/bgimg.jpg");
        background-size: 100% 100%;
        padding: 0 0 0.3rem 0;
    }
    .account{
        position: absolute;
        width: 100%;
        height: 0.3rem;
        background: white;
        padding: .07rem .07rem .07rem .07rem;
        box-sizing: border-box;
        
    }
</style>


