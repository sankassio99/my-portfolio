<template>
    <!-- effect wrap start  -->
    <div class="effect-wrap">
        <div class="effect effect-1">
        
        </div>
        <div class="effect effect-2" >
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        </div>
        <div class="effect effect-3"></div>
        <div class="effect effect-4"></div>
        <div class="effect effect-5">
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.effect-wrap .effect{
    position: absolute;
    z-index: 1;
}

.effect-1{
    width: 30px;
    height: 30px;
    border: 4px solid #8a49ff;
    right: 10%;
    bottom: 10%;
    animation: spin 10s linear infinite;
}
.effect-2{
    left: 3%;
    bottom: 20%;
    width: 20%;
    width: 40px;
    display: flex ;
    flex-wrap: wrap ;
    justify-content: space-between;
    animation: topBounce 3s ease-in-out infinite;
}
.effect-2 div{
    height: 3px;
    width: 3px;
    background-color: #ff9c07;
    margin: 0 3px 8px;
}
.effect-3 {
    height: 180px;
    width: 180px;
    border: 25px solid red;
    border-radius: 50%;
    left: 50%;
    top: -120px;
    animation: leftBounce 3s ease-in-out infinite;
}
.effect-4 {
    border-top: 30px solid transparent;
    border-left: 30px solid #06d79c;
    left: 30%;
    top:20%;
    animation: spin 15s linear infinite;
}
.effect-4:before {
    content: '';
    border-top: 30px solid transparent;
    border-left: 30px solid #06d79c;
    left: -36px;
    top:-25px;
    position: absolute;
    opacity: 0.5;
}
.effect-5 {
    height: 50px;
    width: 50px;
    right: 10%;
    top: 30%;
    display: flex;
    justify-content: space-between;
    border-radius: 50%;
    overflow: hidden;
    animation: spin 10s linear infinite;
}
.effect-5 div {
    width: 1px ;
    background-color: #4dd0e1;
}
@keyframes spin{
    0%{
        transform: rotate(0deg);
    }
    100%{
        transform: rotate(360deg);
    }
}
@keyframes topBounce{
    0%, 100%{
        transform: translateY(0);
    }
    50%{
        transform: translateY(25px);
    }
}
@keyframes leftBounce{
    0%, 100%{
        transform: translateX(0);
    }
    50%{
        transform: translateX(25px);
    }
}
</style>