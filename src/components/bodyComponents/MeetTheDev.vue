<template>
    <div id="meetDiv">
        <h1>Hello, Im the Dev!</h1>
        <img src="https://images.unsplash.com/photo-1552053831-71594a27632d?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=612&q=80" alt="Dog Dev">
    </div>
</template>

<script>
    export default {
        name: "MeetTheDev"
    }
</script>

<style scoped>
    #meetDiv {
        grid-column: 2;
    }

    h1 {
        margin-top: 5vh;
        color: #182825;
    }

    img {
        margin-top: 2vh;
        height: 60vh;
    }
</style>