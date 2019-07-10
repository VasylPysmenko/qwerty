<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style>
 @import "http://cdn.jsdelivr.net/npm/animate.css@3.5.1";
 body {
   background: rgb(223, 223, 223);
   font-family: Arial, Helvetica, sans-serif;
 }
 html,body {
   height: calc(100% - 50px);
 }
 #app{
   background: #fff;
   width: 50%;
   padding: 30px;
   border-radius: 10px;
   margin: 50px auto 0 auto;
   height: calc(60% - 50px);
 }
</style>
