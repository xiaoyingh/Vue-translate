<template>
  <div id="translateOutput">

    <h2>{{translatedText}}</h2>
  </div>
</template>

<script>
  export default {
    name: 'translateOutput',
    props:[
        "translatedText"
    ]
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  #translateOutput{
    width: auto;
    background-color: #ccc;
  }
  h2{
    margin-top: 50px;
    background-color: #ccc;
  }
</style>
