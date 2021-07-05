<template>
  <div class="jumbotron">

    <h2>Questo e il mio primo Jumbotron</h2>

  </div>
</template>

<script>
export default {

  name: 'Hero',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

  .jumbotron{
    height: 400px;
    width: 100%;
    background-image: url(../assets/1.jpg);
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: 10px;
    margin-bottom: 200px;
  }

  h2{
    font-size: 50px;
    text-transform: uppercase;
    color: rgb(184, 184, 184);
    padding: 30px;
    border-radius: 20px;
    background-color: rgba(0, 0, 0, 0.534);
  }

</style>
