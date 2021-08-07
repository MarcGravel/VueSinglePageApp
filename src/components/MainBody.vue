<template>
    <div id="mainBody">
        <SidePanel></SidePanel>
        <MeetTheDev></MeetTheDev>
        <MeetTheTeam></MeetTheTeam>
    </div>
</template>

<script>
import SidePanel from './bodyComponents/SidePanel.vue'
import MeetTheDev from './bodyComponents/MeetTheDev.vue'
import MeetTheTeam from './bodyComponents/MeetTheTeam.vue'

    export default {
        name: 'MainBody',
        components: {
            SidePanel,
            MeetTheDev,
            MeetTheTeam
        }
    }
</script>

<style scoped>
    #mainBody{
        width: 100vw;
        height: 77vh;
        background-color: rgb(253, 253, 253);
        display: grid;
        grid-template-columns: repeat(3, 1fr);
    }
</style>