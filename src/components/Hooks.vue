<template>
    <div>
        <input type="text" placeholder="Ingrese una palabra.." class="textbox" >
    </div>
</template>

<script>
    export default {
        name: "Hooks",
        data() {
            return {
                name: ""
            }
        }
    }
</script>
    
<style>
    .textbox{
        display: grid;
        grid-template-rows: auto;
        justify-items: center;
        align-items: center;
        margin: 0 auto 2rem;
    }
</style>