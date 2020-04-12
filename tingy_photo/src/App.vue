<template>
  <div id="app">
    <div id="nav">
    <div id ="title">
    Eric Tingey Photography
    </div>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/contact">Contact</router-link>
    </div>

    <router-view/>
    <div class = "footer">Steven Chevrier - <a href= "https://www.github.com/slchev/creative_project_3">Github</a>
    </div>
  </div>

</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin:-8px;
  background-color:#e4f0f2;

}

#nav {
  padding: 10px;
    text-align: right;
    border-bottom: 1px solid #000000;
    background-color:#c95b5b;

}
.footer{
text-align:center;
background-color: #c95b5b;
margin:0;
padding:5px;
margin-bottom:-30px;
color:#8ae8ff;

}
#title{
padding:5px;
padding-top:10px;
padding-bottom:-10px;
margin-bottom:-5px;
text-align:left;
font-weight:bold;
color:#8ae8ff;
font-size:25px;
}

#nav a {
  font-weight: bold;
  color: #8ae8ff;
}

#nav a.router-link-exact-active {
  color: #62a5b5;

}
</style>
