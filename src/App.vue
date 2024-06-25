<template>
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> |
    <router-link to="/about">Resume</router-link> |
    <router-link to="/about">Skills</router-link> |
    <router-link to="/about">Education</router-link> |
    <router-link to="/about">Work Experience</router-link> |
    <router-link to="/about">Projects</router-link> |
    <router-link to="/about">Testimonials</router-link> |
    <router-link to="/about">Reach Me</router-link> 






  </nav>
  <router-view/>
</template>

<style>

template {


}
#app {
  
  text-align: center;
  color: #2c3e50;
  background-color:#332234;

}

nav {
  padding: 25px;
  font-family: "Inter", sans-serif;
  background-color:#543656;

  
}
nav a:hover {
  color:#9d5ea2;
  text-decoration: underline;
  

}

nav a {
  font-weight: bold;
  color: white;
  text-decoration:none;
}

nav a.router-link-exact-active {
  color:#9d5ea2;
}
</style>
