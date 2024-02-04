<template>
    <div id="events">
        <EventsComp />
    </div>
</template>
<script>
import EventsComp from '../components/EventsComp.vue';
export default {
    components: { 
        EventsComp
    }
}
</script>
<style scoped>
    #events{
        overflow: hidden;
        /* padding: 10px; */
        min-height: 100vh;
        padding: 70px;
    }
    /* #events{
        padding-top: 70px;
    } */
</style>