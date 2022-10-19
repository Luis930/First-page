<template>
  <div class="container">
    <nav class="navbar navbar-dark bg-primary my-3 col-sm-12 col-md-12 col-lg-12 col-xl-12">
       <ul class="mx-auto">
        <NuxtLink to="/baseball" class="but text-decoration-none">Baseball</NuxtLink>
        <NuxtLink to="/basketball" class="but text-decoration-none">Basketball</NuxtLink>
        <NuxtLink to="/soccer" class="but text-decoration-none">Soccer</NuxtLink>
       </ul>
    </nav>
  </div>
</template>

<style>
nav{
  height: 50px;
  border-radius: 10px;
  width: 10px;

}
.but{
  border-radius: 10px;
  background-color: grey;
  text-align: center;
  color: black;
  line-height: 30px;
  padding-left: 20px;
  padding-right: 20px;
  margin-right: 20px;
}

</style>
