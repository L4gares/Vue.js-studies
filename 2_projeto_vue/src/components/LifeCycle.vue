<template>
    <h1>Meu nome is: {{ nome }}</h1>
</template>

<script>
export default{
    name: 'LyfeCycle',
    data(){
        return {
            nome: 'Ainda nao sei'
        }
    },
    created(){
        setTimeout(() => {
            this.nome = 'Carlos'
        }, 1000)
        
    },
    mounted(){
        
            setTimeout(() => {
            this.nome = 'Pedro'
        }, 2000)
        
           
        
    }
}
</script>