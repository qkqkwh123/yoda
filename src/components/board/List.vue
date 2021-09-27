<template>
  <!DOCTYPE html>
  <html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yoda Project CSV </title>
  </head>
  <body>

  <input type="file" id="csvFileInput" style="padding-bottom: 15px">
  <table id="csvRoot"></table>


  </body>
  </html>

</template>

<script>

import Vue from 'vue'
import VuePapaParse from 'vue-papa-parse'
Vue.use(VuePapaParse)


export default {

}
</script>
<!--

h3 {
  margin: 40px 0 0;
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
  color: #42b983;
}

-->
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
table {
  border-collapse: collapse;
  border-radius: 5px;
  box-shadow: 0 0 4px rgba(0, 0, 0, 0.25);
  overflow: hidden;
  font-family: "Quicksand", sans-serif;
  font-weight: bold;
  font-size: 14px;
}

th {
  background: #009578;
  color: #ffffff;
  text-align: left;
}

th,
td {
  padding: 10px 20px;
}

tr:nth-child(even) {
  background: #eeeeee;
}
</style>

