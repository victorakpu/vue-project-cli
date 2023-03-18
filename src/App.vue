
<template>
  <div class="router">
    <div class="head">

      <h1 class="app-header">Counter/Routing</h1>
      
    </div>
    
    <nav>
      <ul>
        <li class="link"><router-link to="/">Home</router-link></li>
        <li class="link"><router-link to="/counter">Counter</router-link></li>
        <li class="link"><router-link to="/about">About</router-link></li> 
        <li class="link"><router-link to="/contact-us">Contact Us</router-link></li>
        
      </ul>
    </nav>
  </div>
  <router-view />
</template>


<style>

@media (prefers-reduced-motion: no-preference) {
  .App-logo {
    animation: App-logo-spin infinite 20s linear;
  }
}
@media (min-width: 600px) and (max-width: 900px) {
  .App-logo {
    animation: App-logo-spin infinite 20s linear;
  }
}
  
  
  
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  
  margin-top: 0px;
}
body{
  background-color: white;
  margin: 0px;
}
.router {
  background-color: #660da2;
  color:white;
  margin: 0px;
  padding: 4rem;}
   
  .link:first-child {
    margin-left: 0;
  }
  nav {
    
    float: right;
    
  }
  nav ul{
  list-style: none;
  margin: 0;
  padding: 0;
  
}
nav li{
  display: inline-block;
  margin: 20px;
}
nav li:first-child{
  margin-left: 0;
}
nav a{
  display: inline;
  font-size: default;
  font-weight: bold;
  padding: 10px;
  text-decoration: none;
  color:white;
}
.head{
  float:left;
  
  
}
nav ul li a:hover{
  color:rgba(198,123,17,1) ;
}
.app-header{
  margin-top: 0px;
  margin-bottom: 0px;
  color: white;
  font-size: 30px;
  font-weight: bold;
  text-align: center;
  padding: 0px;
}
</style>

