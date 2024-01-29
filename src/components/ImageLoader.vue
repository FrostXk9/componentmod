<template>
    <div class="cont">
        <div class="cube">
            <div class="face front">lprem</div>
            <div class="face back">ipsum</div>
            <div class="face left">dolor</div>
            <div class="face right">fogu</div>
            <div class="face top">fuga</div>
            <div class="face bottom">indte</div>
        </div>
    </div>
</template>
<script>
import AOS from 'aos';

export default {
    mounted(){
        AOS.init();
    }
}
</script>
<style scoped>
        .cont {
            perspective: 800px;
            perspective-origin: 50% 50%;
            width: 200px;
            height: 200px;
            position: relative;
            margin: 100px auto;
        }

        .cube {
            width: 100%;
            height: 100%;
            position: absolute;
            transform-style: preserve-3d;
            animation: rotateCube 5s infinite linear;
        }

        .face {
            position: absolute;
            width: 200px;
            height: 200px;
            background-color: rgba(0, 255, 30, 0.7);
            border: 1px solid #000;
        }

        .face.front  { transform: translateZ(100px); }
        .face.back   { transform: rotateY(180deg) translateZ(100px); }
        .face.left   { transform: rotateY(-90deg) translateZ(100px); }
        .face.right  { transform: rotateY(90deg) translateZ(100px); }
        .face.top    { transform: rotateX(90deg) translateZ(100px); }
        .face.bottom { transform: rotateX(-90deg) translateZ(100px); }

        @keyframes rotateCube {
            from { transform: rotateY(0deg); }
            to   { transform: rotateY(360deg); }
        }
</style>