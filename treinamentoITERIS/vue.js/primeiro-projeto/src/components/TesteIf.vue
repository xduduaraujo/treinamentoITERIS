<template>
    <div class="testeif">
        <h1 v-if="podeVer">Teste 1</h1>
        <h1 v-else>Teste 2</h1>
    </div>
</template>

<script>
export default {
    name: 'TesteIf',
    data() {
        return{
            podeVer: true
        }
    }
}
</script>

<style scoped>

</style>