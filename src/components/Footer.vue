<template>
<div>

<div id="footer">
    <ul>
      <li><a href="">About Historyden</a></li>
        <li><a href="">Careers</a></li>
      <li><a href="">Help</a></li>
      <li><a href="">Contact Us</a></li>
    </ul>
    <p class="foot">&copy; 2020 Historyden.com. All Rights Reserved.</p>
  </div>
  <br>

</div>
</template>

<script>
export default {
 
}
</script>

<style scoped>
body {
 font-family: verdana, Georgia, serif;
 font-size: 14px;
}
#footer {
 background-color: #5c755e;
 margin: 10px;
 height: 75px;
 clear: both;
 border-radius: 5px;
 color: #efe5d0;
 text-align: center;
 padding: 15px;
 font-size: 120%;
}

#footer ul {
 padding: 5px;
 list-style-type: none;
 text-align: center;
 margin: 10px;
}
#footer ul li {
 display: inline;
}
#footer ul li a {
 text-decoration: none;
 font-family: Arial;
 padding: .2em 1em;
 color: #efe5d0;
 background-color: #5c775e;
}
#footer ul li a:hover {
 color: #000;
 background-color: #fff;
}
.foot {
  margin: 10px;
 animation: long 40s both infinite;
 animation-timing-function: ease-in-out,
}
@keyframes long {
 0% {
  transform: translateX(-1200px);
 }
 100% {
  transform: translateX(1130px);
 }
}
</style>