<script>
import TheWelcome from '../components/TheWelcome.vue'
export default{
    components:{
      TheWelcome
    },
    data(){
      return{
        titulo: 'Home'
      }
    },
    methods:{

    }
}
</script>

<template>
  <div id="divHomeView" >
    <h1 v-html="titulo"></h1>
    <img alt="Vue logo" src="@/assets/link.jpg" />

    <main>
      <TheWelcome />
    </main>
  </div>

</template>

<style scoped>
#divHomeView{
  background-color: lightgreen;
  color: black;
  margin:2%;
}

</style>
