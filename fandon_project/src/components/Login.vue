<template>
<mt-header class="header" fixed title="">
  <mt-button  class="jump" slot="right">跳过</mt-button>
</mt-header>

</template>

<script>
export default {
  name: 'Login',
  data () {
    return {
     msg :"333"
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.header{
  background:#42b983
}
.jump{
  color:#000
}
</style>
