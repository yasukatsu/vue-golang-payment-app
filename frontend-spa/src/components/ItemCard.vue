<template>
  <div class="itemcard">
    <h1>{{ item.Name }}</h1>
    <h2>{{ item.Description }}</h2>
    <h2>{{ item.Amount }}円</h2>
  </div>
</template>

<script>
export default {
  name: 'ItemCard',
  props: [
    'item'
  ]
}
</script>

<style scoped>
h1,
h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: aqua;
}
button {
  margin: 10px 0;
  padding: 10px;
}
.itemcard {
  border: solid 1px gray;
}
</style>
