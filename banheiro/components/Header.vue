<template>
    <header>
        <nav>
            <a href="" class="link">Fila de espera</a>
            <a href="" class="link">Já foram</a>
        </nav>
    </header>
</template>
<script>
    export default {
        data() {
           return {
                cumprimento: ''
           }
        },
        methods: {
            
        }
    }
</script>
<style>
    nav{
        height: 50px;
        display: flex;
        align-items: center;
        justify-content: center;
        background-color: rgb(125,0,150);
    }
    a.link{
        display: flex;
        align-items: center;
        justify-content: center;
        width: 50%;
        height: 100%;
        text-align: center;
        color: rgb(240,240,240);
        transition: background-color 0.5s;
    }
    a.link:nth-of-type(odd){
        border-right: 1px solid white;
        border-collapse: collapse;
    }
    a.link:hover{
        background-color: rgb(200, 50, 50);
    }
</style>