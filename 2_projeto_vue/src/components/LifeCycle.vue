<template>
    <h1>Meu nome é: {{ nome }}</h1>
</template>

<script>
export default {
    name: 'LifeCycle',
    data() {
        return {
            nome: 'Ainda não sei'
        }
    },
    created(){
        setTimeout(() => {
            this.nome = 'Kasteh'
        }, 1000);
    },

    mounted() {
        setTimeout(() => {
            this.nome = 'Deyvid Kasteh'
        }, 3000);
    }
}
</script>