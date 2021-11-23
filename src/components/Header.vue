<template>
  <header>
    <h1>La mia prima app con Vue CLI!</h1>
    <h3>(Questo è l'header) </h3>
  </header>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style scoped>
h1,h3{
  color: blueviolet; 
  padding: 50px 0;
}

h3{
  padding-top: 0;
}

header{
  background-color: pink;

}

</style>