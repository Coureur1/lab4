<template>
  <div id="app">
    <div class="header">
      <router-link to="/">
        <div class="logo">
          <img src="/ordinary.png" />
        </div>
      </router-link>
      <div class="title">
        <h1>Museum of Ordinary Objects</h1>
      </div>
    </div>
    <div class="content">
      <router-view />
    </div>
    <div class="footer">
      <router-link to="/admin">Admin</router-link>
      <a class="github" href="https://github.com/Coureur1/lab4.git">GITHUB</a>
    </div>
  </div>
</template>

<style>
html {
  box-sizing: border-box;
}

body {
  font-family: "Montserrat", sans-serif;
  font-size: 16px;
  background: #fff;
  padding: 0px;
  margin: 0px;
}

/* Header */
.header {
  display: flex;
  padding: 10px 100px 0px 100px;
  background-color: #5bdeff;
  color: #1c454f;
}

.title {
  margin-top: 5px;
}

.title h1 {
  font-size: 30px;
}

.content {
  padding: 20px 100px;
  min-height: 500px;
}

/* Footer */
.footer {
  height: 50px;
  padding: 20px 100px 0px 100px;
  background: #e3e3e3;
  font-size: 12px;
}

.footer a {
  color: #000;
  font-weight: bold;
  padding: 0px 10px 0px 10px;
}

h1 {
  font-size: 20px;
}

h2 {
  font-size: 14px;
}
</style>
