<template >
  <div>
    <nav class="navbar navbar-expand-lg">
  <div class="container-fluid ">
      <router-link to="/" class="logo">
          <img src="https://i.postimg.cc/sg3wGdBx/LINDOKUHLE-MGOQI-logo-2-1.png" width="90" height="35">
      </router-link>
  
    <div class="collapse navbar-collapse d-flex" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
        <router-link to="/" class="nav-link m-0 home">Home</router-link>
       </li>
        <li class="nav-item">
        <router-link to="/about" class="nav-link m-0 one">About</router-link>
       </li>
       <li class="nav-item">
        <router-link to="/contact" class="nav-link m-0 one">Contact</router-link>
       </li>
      </ul>
    </div>
  </div>
</nav>
  </div>
</template>
<script>
export default {
  
}
</script>
<style scoped>
nav{
  background-color:#100f0f;
}
nav li.router-link-exact-active {
  color: #f1f1f1;
}
.nav-link{
  color: #f1f1f1;
  text-align: end;
}
.home{
  color: #EF5B0E;
}
.one{
  padding-left: 9rem;
}
.logo{
  margin-left: 20px;
}
.container-fluid{
  display: flex;
  width: 0;
  margin: 0;
  padding: 0;
}
.collapse{
  margin-left: 74rem;
}
</style>