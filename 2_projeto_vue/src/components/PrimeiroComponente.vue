<template>
    <div>
    <h1>Olá vue!</h1>
    <p>Meu nome é {{ nome }} e minha função é {{profissao}}</p>
    </div>
</template>

<script>
export default {
    name: 'PrimeiroComponente',
    data() {
        return {
            nome: "Deyvid",
            profissao: "programador"
        }
    }
}
</script>