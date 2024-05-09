<template>
  <div>
    <primeiroComponente/>
    <p>O data de app is: {{ testando }}</p>
    
    <LifeCycle/>
    <People/>
    
  </div>
</template>

<script>

  import PrimeiroComponente from './components/PrimeiroComponente.vue'
  import LifeCycle from './components/LifeCycle.vue'
  import People from './components/People.vue'



  
  export default{
    name: 'App',

    components: {
      PrimeiroComponente,
      LifeCycle,
      People
    
    },
    data(){
      return{
        testando: "Test"
      } 
    }
  }

</script>
