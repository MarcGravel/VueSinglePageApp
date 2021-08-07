<template>
    <div id="footer">
        <h4>© Copyright Statement</h4>
        <h5>Test Page</h5>
    </div>
</template>

<script>
    export default {
      name: "BottomFoot"  
    }
</script>

<style scoped>
    #footer {
        height: 10vh;
        width: 100vw;
        background-color: #182825;
        display: grid;
        grid-template-columns: 1fr 5fr 1fr;
        align-items: center;
    }

    h4, h5 {
        color: #EFE7DA;
    }

    h5 {
        grid-column: 3;
    }
</style>