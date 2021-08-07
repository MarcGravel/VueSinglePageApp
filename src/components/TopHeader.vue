<template>
  <div id="topHead">
    <img id="logo" src="https://images.unsplash.com/photo-1518837695005-2083093ee35b?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80" alt="Vue Logo">
    <h1>First Vue Page</h1>
    <div id="navBtns">
        <button id="home">Home</button>
        <button id="shop">Shop</button>
        <button id="about">About Us</button>
        <button id="careers">Careers</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'TopHeader'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    #topHead {
        width: 100vw;
        height: 13vh;
        background-color: #182825;
        display: grid;
        grid-template-columns: 1fr 7fr 4fr;
        align-items: center;
    }

    #logo {
        width: 150px;
        grid-column: 1;
        justify-self: end;
        border-radius: 50px;
    }

    h1 {
        font-size: 4em;
        color: #EFE7DA;
        font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    }

    #navBtns {
        grid-column: 3;
    }

    button {
        margin-left: 1vw;
        height: 4vh;
        padding: 0 2vw 0 2vw;
        background-color: #EFE7DA;
        color: #182825;
        border-radius: 12px;
        
    }
</style>