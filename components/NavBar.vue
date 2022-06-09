<template>
  <div>
    <b-navbar toggleable="lg" type="dark" variant="success">
      
      <img src="https://avatars.githubusercontent.com/u/23360933?s=200&v=4" alt="" width="50px" >
      <b-navbar-brand href="#">Frameworks</b-navbar-brand>
      

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item to="/home">Home</b-nav-item>
        </b-navbar-nav>

        <b-navbar-nav>
          <b-nav-item to="/table">Tabla</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
  
</template>

<script>
export default {};
</script>

<style></style>
