<template>
    <div class="contador">
        <p><strong>Contador:</strong> {{number}}</p>
        
        <input type="button" value="-" @click="subtrair()">
        <input type="button" value="+" @click="somar()">
    </div>
</template>

<script>
export default {
    name: 'Contador',
    data() {
        return {
            number: 0
        }
    },
    methods: {  
        somar(){
            this.number = this.number + 1;
        },
        subtrair(){
            this.number = this.number - 1;
        }
    }
}
</script>

<style scoped>

</style>