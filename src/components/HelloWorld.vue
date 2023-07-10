<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
        {{ variable1 }}
    </p>
    <h2>
    {{ numero }} 
    <button @click="incrementar()">+ Incrementar</button>
    <button @click="decrementar()">- Decrementar</button>
    </h2>
    <h1 v-if="numero<=2">
        TEXTO 1
    </h1>
    <h1 v-else>
      TEXTO 2
    </h1>
  </div>
</template>

<script>
export default 
{
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data(){
    return {
       numero: 1,
           }
    },
  
    methods: {
      incrementar(){
        this.numero++
        },
      decrementar(){
        this.numero--
      }
    },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
