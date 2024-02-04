<template>
    <div id="missionPage">
        <MissionComp />
    </div>
</template>
<script>
import MissionComp from '../components/MissionComp.vue';

export default {
    components : {
        MissionComp
    }
}
</script>
<style>
    #missionPage{
        display: flex;
        justify-content: center;
        align-items: center;
        min-height: 100vh;
    }
</style>