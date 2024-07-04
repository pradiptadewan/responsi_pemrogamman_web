<template>
    <nav class="nav">
     <ul>
      <li> <a href="">ABOUT</a></li>
      <li><a href="">MY PROJECT</a></li>
      <li><a href="">CONTACT</a></li>

    </ul>
  </nav>
</template>

<style scoped>
.nav {
  text-align: right; 
  background-color: midnightblue;
}

.nav ul {
  list-style-type: none;
  padding: 0;
  margin: 0;
}

.nav li {
  display: inline-block;
  margin-left: 10px; 
  padding: 10px;
}

.nav li:first-child {
  margin-left: 0;
}

.nav li a {
  text-decoration: none;
  color: #ffffff;
  padding: 10px;
  display: block;
}

.nav li a:hover {
  background-color: #ff01ff;
}

</style>