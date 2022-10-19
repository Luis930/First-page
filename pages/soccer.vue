<template>
  <div class="container">
    <div class="row">
      <div class="card-group my-4">
        <div class="card">
          <img src="../static/Images/MC.jpg" class="card-img-top carta" alt="">
          <div class="card-body">
            <h5 class="card-title p-3 text-justify">Manchester City</h5>
            <p class="card-text">Manchester City Football Club are an English football club based in Manchester that competes in the Premier League, the top flight of English football. Founded in 1880 as St. Mark's (West Gorton), they became Ardwick Association Football Club in 1887 and Manchester City in 1894.</p>
            <p class="card-text"><small class="text-muted"></small></p>
          </div>
        </div>
        <div class="card">
          <img src="../static/Images/RM.jpg" class="card-img-top carta" alt="">
          <div class="card-body">
            <h5 class="card-title">Real Madrid</h5>
            <p class="card-text p-3 text-justify">Real Madrid Club de Fútbol, meaning Royal Madrid Football Club, commonly referred to as Real Madrid, is a Spanish professional football club based in Madrid.

                Founded in 1902 as Madrid Football Club, the club has traditionally worn a white home kit since its inception.</p>
            <p class="card-text"><small class="text-muted"></small></p>
          </div>
        </div>
        <div class="card">
          <img src="../static/Images/BM.jpg" class="card-img-top carta" alt="">
          <div class="card-body">
            <h5 class="card-title">Bayern Munich</h5>
            <p class="card-text p-3 text-justify">Fußball-Club Bayern München , also known as FC Bayern , Bayern Munich, or simply Bayern is a German professional sports club based in Munich, Bavaria. It is best known for its professional men's football team, which plays in the Bundesliga, the top tier of the German football league system.</p>
            <p class="card-text"><small class="text-muted"></small></p>
          </div>
        </div>
      </div>
    </div>
    <NuxtLink to="/" class="mode text-decoration-none my-2">HOME</NuxtLink>
  </div>

 </template>

<style>
 .carta{
  height: 330px;
 }
 .mode{
  border-radius: 10px;
  background-color: grey;
  text-align: center;
  color: black;
  padding: 12px;
  float: right;
 }
</style>
