<template>
    <aside>
        <div id="ad">
            <p>Advert</p>
        </div>
    </aside>
</template>

<script>
    export default {
        name: "SidePanel"
    }
</script>

<style scoped>
    aside {
        grid-column: 1;
        width: 15vw;
        height: 100%;
        background-color:#EFE7DA;
        display: grid;
        justify-items: center;
        align-items: center;
    }

    #ad {
        width: 10vw;
        height: 20vh;
        background-color: #182825;
    }

    p {
        margin-top: 8vh;
        color: #EFE7DA;
    }
</style>