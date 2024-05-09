<template>
   <div>
        <h1>Hello Vue!</h1>
        <p>My name is {{ nome }} and i work as {{ profissao }} </p>
   </div>
</template>

<script>
     
    export default{
        name: 'PrimeiroComponente',
        data() {
            return {
                nome: "Daniel Lagares",
                profissao: "Programmer"
            }
        }
    }

</script>