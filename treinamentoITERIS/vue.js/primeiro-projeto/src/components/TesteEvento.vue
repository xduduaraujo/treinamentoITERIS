<template>
    <div class="teste-evento">
        <h2>Teste evento</h2>
        <p @click="deixarMaiuscula()">{{ mensagem }}</p>
    </div>
</template>

<script>
export default {
    name: 'TesteEvento',
    data() {
        return {
            mensagem: 'O rato roeu a roupa do rei de Roma.'
        }
    },
    methods: {
        deixarMaiuscula() {
            this.mensagem = this.mensagem.toUpperCase();
        }
    }
}
</script>

<style scoped>

</style>