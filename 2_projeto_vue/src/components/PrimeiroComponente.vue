<template>
   <div>
        <h1>Hello Vue!</h1>
        <p>My name is {{ nome }} andi work as {{ profissao }} </p>
   </div>
</template>

<script>
     
    export default{
        name: 'PrimeiroComponente',
        data() {
            return {
                nome: "Matheus",
                profissao: "Programmer"
            }
        }
    }

</script>