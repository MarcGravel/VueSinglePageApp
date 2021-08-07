<template>
    <div id="theTeam">
        <h1>We are the Team!</h1>
        <img src="https://images.unsplash.com/photo-1600804340584-c7db2eacf0bf?ixid=MnwxMjA3fDB8MHxzZWFyY2h8NHx8cHVwcHl8ZW58MHx8MHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="Pup 1">
        <img src="https://images.unsplash.com/photo-1591160690555-5debfba289f0?ixid=MnwxMjA3fDB8MHxzZWFyY2h8M3x8cHVwcHl8ZW58MHx8MHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="Pup 2">
        <img src="https://images.unsplash.com/photo-1510337550647-e84f83e341ca?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1189&q=80" alt="Pup 3">
    </div>
</template>

<script>
    export default {
        name: "MeetTheTeam"
    }
</script>

<style scoped>
    #theTeam {
        justify-self: center;
        align-self: center;
        grid-column: 3;
        display: grid;
        justify-items: center;
        align-items: center;
    }
    
    h1 {
        color: #182825;
    }

    img {
        margin-top: 1vh;
        display: block;
        height: 20vh;
        object-fit: cover;
    }
</style>