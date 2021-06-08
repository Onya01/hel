<template>
  <div id="navbar">
    <nav>
      <ul>
        <li><router-link to="/">Home</router-link></li>
        <li><router-link to="/ancientgreece">Ancient Greece</router-link></li>
        <li><router-link to="/ancientrome">Ancient Rome</router-link></li>
        <li><router-link to="/ancientwarII">Ancient war II</router-link></li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
#navbar {
  text-align: center;
  list-style-type: none;
  padding: 5px;
  background-color: #000;
  margin: 10px;
  border-radius: 5px;
  animation: drive 10s;
  transition: transform 1s 1s ease-in-out;
}
#navbar ul li {
  text-align: center;
  list-style: none;
  display: inline-block;
  margin: 10px;
  position: relative;
}
#navbar ul li a {
  text-decoration: none;
  color: #fff;
  text-transform: uppercase;
}
#navbar ul li::after {
  content: "";
  height: 3px;
  width: 0;
  background: #009688;
  position: absolute;
  left: 0;
  bottom: -10px;
  transition: 0.5s;
}
#navbar ul li:hover:after {
  width: 100%;
}
@keyframes drive {
  0% {
    transform: translateX(-1900px);
  }
  100% {
    transform: translateY(0px);
  }
}
</style>