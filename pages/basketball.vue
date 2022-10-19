<template>
  <div class="container">
    <div class="row">
      <div class="card-group my-4">
        <div class="card">
          <img src="../static/images/MJ.jpg" class="card-img-top carta" alt="">
          <div class="card-body">
            <h5 class="card-title">Michael Jordan</h5>
            <p class="card-text p-3 text-justify">Michael Jeffrey Jordan (born February 17, 1963), also known by his initials MJ, is an American businessman and former professional basketball player. His biography on the official NBA website states: "By acclamation, Michael Jordan is the greatest basketball player of all time.</p>
            <p class="card-text"><small class="text-muted"></small></p>
          </div>
        </div>
        <div class="card">
          <img src="../static/Images/GV.jpg" class="card-img-top carta" alt="">
          <div class="card-body">
            <h5 class="card-title">Greivis Vasquez</h5>
            <p class="card-text p-3 text-justify">Greivis Josué Vásquez Rodríguez (born January 16, 1987) is a former Venezuelan professional basketball player, who spent six seasons in the NBA. He is currently a coach, most recently working as the associate head coach for the Erie BayHawks of the NBA G League.</p>
            <p class="card-text"><small class="text-muted"></small></p>
          </div>
        </div>
        <div class="card">
          <img src="../static/Images/LJ.jpg" class="card-img-top carta" alt="">
          <div class="card-body">
            <h5 class="card-title">Lebron James</h5>
            <p class="card-text p-3 text-justify">LeBron Raymone James Sr. Born December 30, 1984, is an American professional basketball player for the Los Angeles Lakers of the National Basketball Association (NBA). Nicknamed "King James", he is widely considered one of the greatest players.</p>
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
