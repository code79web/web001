<template>
    <div class="container">
        <div class="denglu">
            <input type="text" placeholder="账号" class="shuruk">
            <br>
            <input type="password" placeholder="密码" class="shuruk1">
            <br>
            <button class="dlan">登录</button>
            <br style="clear:both" />
            <a href="" class="zhuce">没有账号？去注册</a>
        </div>

    </div>

</template>



<script lang="ts">
export default {
    name: "DengLu1"
}
</script>

<script lang="ts" setup>



</script>


<style scoped>
.container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    width:100%;
    background-image: url('../assets/beijing2.png');
    background-repeat:no-repeat;
    background-size: cover;
}


.denglu {
    width: 25%;
    height: 300px;
    background-color: #353943;
    border-radius: 10px;
    box-shadow: 0 4px 8px;
    text-align: center;

}

.dlan {
    width: 170px;
    height: 35px;
    font-size: 13px;
    color: white;
    background-color: #22ca69;
    margin-top: 10px;
    border-radius: 5px;
    border: 1px solid white;
}

.shuruk {
    height: 30px;
    margin-top: 65px;
    border-radius: 5px;
    background-color: transparent;
    border: 1px solid white;
    color: azure;
}

.shuruk1 {
    height: 30px;
    margin-top: 10px;
    border-radius: 5px;
    background-color: transparent;
    border: 1px solid white;
    color: azure;
}

input[type="text"]::placeholder,input[type="password"]::placeholder {
    color: white;
}

.zhuce {
    position: relative;
    bottom: -25%;
    right: -30%;
    font-size: 13px;
    text-decoration: none;
    color: white;

}
</style>