<template>
  <div>
    <br>
    <div id="header">
    <h3>historyden.com</h3>
  </div>
  </div>
</template>

<script>

export default {
  name: 'Header',
  props: {
    header: String
  }
}
</script>
4
<style scoped>
#header {
 background-color: #5c755e;
 margin: 10px;
 height: 120px;
 border-radius: 5px;
}
h3 {
 font-size: 300%;
 text-align: center;
 color: #e5e4d7;
 font-family: "Century Gothic", "Gill Sans", Arial, sans-serif;
 margin: 0px;
 position: relative;
 top: 50%;
 -webkit-transform: translateY(-50%);
 -ms-transform: translateY(-50%);
 transform: translateY(-50%);
}
</style>
