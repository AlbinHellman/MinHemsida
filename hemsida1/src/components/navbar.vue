<template>
<nav class="navbar">
  <div class="container-fluid">
    <div class="space">
    <a class="navbar-brand" href="#">Alin Hellman</a>
    </div>
    <div class="space-between">
    <a class="navbar-brand" href="#">Homepage</a>
    </div>
    <div class="space-between">
    <a class="navbar-brand" href="#">About</a>
    </div>
    <div class="space-between">
    <a class="navbar-brand" href="#">Contact</a>
  </div>
  </div>
</nav>

</template>
<script>
export default {
  name: 'MyNavbar'
}
</script>

<style scoped>


.navbar {
  background-color: black;
  height: 10rem;
}

.navbar-brand {
  color: white;
    font-family: Arial, Helvetica, sans-serif;
  text-decoration: none;
  font-size: 1.3rem;
}

.space {

 margin-left: 5rem;
 margin-top: 4rem;
 margin-right: 28rem;
}

.space-between {
  margin: 3rem;
  padding-top: 1rem;
}



navbar-nav {
  display: flex;
}

.container-fluid {

  display: flex;

}



</style>