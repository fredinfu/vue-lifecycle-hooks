<template>
    <div>
        <input type="text" v-model="modelName" placeholder="Ingrese una palabra.." class="textbox" >
    </div>

</template>

<script>
    export default {
        name: "Hooks",
        data() {
            return {
                modelName: ""
            }
        },
        beforeCreate: function () {
            console.log('beforeCreate')
        },
        created: function () {
            console.log('created')
        },
        beforeMount: function () {
            console.log('beforeMount')
        },
        mounted: function () {
            console.log('mounted')
        },
        beforeUpdate: function () {
            console.log('beforeUpdate')
        },
        updated: function () {
            console.log('updated')
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