<template>
  <div class="container">
    <div class="row">
      <div class="card-group my-3">
        <div class="card">
          <img src="../static/Images/DC.jpg" class="card-img-top carta" alt="">
          <div class="card-body">
            <h5 class="card-title">Washington DC</h5>
            <p class="card-text p-3 text-justify">
              Nationals Park is a baseball stadium along the Anacostia River in the Navy Yard neighborhood of Washington, D.C. Home to Major League Baseball's Washington Nationals since its completion in 2008, it was the first LEED-certified green major professional sports stadium in the United States.</p>
            <p class="card-text"><small class="text-muted"></small></p>
          </div>
        </div>
        <div class="card">
          <img src="../static/Images/LA.jpg" class="card-img-top carta" alt="">
          <div class="card-body">
            <h5 class="card-title">Dodgers</h5>
            <p class="p-3 lineal">Dodger Stadium is a baseball stadium in the Elysian Park neighborhood of Los Angeles, California. It is the home stadium of Major League Baseball's Los Angeles Dodgers. Opened in 1962</p>
            <p class="card-text"><small class="text-muted"></small></p>
          </div>
        </div>
        <div class="card">
          <img src="../static/Images/NY.jpg" class="card-img-top carta" alt="">
          <div class="card-body">
            <h5 class="card-title">New York</h5>
            <p class="card-text text-justify lineal p-3">The current Yankee Stadium is a baseball stadium located in the Bronx, New York City. It is the home field for Major League Baseball's New York Yankees and Major League Soccer's New York City FC. The $2.3 billion stadium, built with $1.2 billion in public subsidies</p>
            <p class="card-text"><small class="text-muted"></small></p>
          </div>
        </div>
      </div>
    </div>
    <NuxtLink to="/" class="mode mb-2 text-decoration-none">HOME</NuxtLink>
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
  padding: 10px;
  float: right;
 }
 ¨.lineal{
  text-align: justify;
  width: 100%;
  margin: auto;
 }
</style>




