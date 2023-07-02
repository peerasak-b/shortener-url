<template>
  <div>
    <div class="header-name">
      <h1>{{ msg }}</h1>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.header-name{
  font-size: 32px;
  vertical-align: middle;
}
</style>
