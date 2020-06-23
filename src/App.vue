<template>
    <div id="app">
        <HelloWorld msg=" Hello Youre App Online now" />
    </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue"

export default {
    name: "App",
    components: {
        HelloWorld,
    },
}
</script>

<style>
*,
*::before,
*::after {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

#app {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    height: 100vh;
    width: 100%;
    font-family: Avenir, Helvetica, Arial, sans-serif;
    color: #000;
}
</style>
