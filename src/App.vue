<template>
  <div>
    <p v-if="age < 18">подросток</p>
    <p v-else-if="age >= 19 && age <=25">молодой чел</p>
    <p v-else="age > 26">мужчина</p>
  </div>
</template>

<script>

export default {
  data(){
    return{
      age: 15
    };
  }
};

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
