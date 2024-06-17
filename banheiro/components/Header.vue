<template>
    <button @click="clica">
        clica
    </button>
</template>
<script>
    export default {
        data() {
           return {
                cumprimento: 'olá, eu sou o Goku!'
           }
        },
        methods: {
            clica(){
                console.log(this.cumprimento)
            }
        }
    }
</script>