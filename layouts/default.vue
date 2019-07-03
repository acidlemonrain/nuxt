<template>
  <div class="b">
    <ul class="nav justify-content-center navbar-dark bg-dark fixed-top">
      <li class="nav-item">
        <nuxt-link to="/">
          <a class="nav-link active" href="#">Attack</a>
        </nuxt-link>
      </li>
      <li class="nav-item">
        <nuxt-link to="/about">
          <a class="nav-link active" href="#">Why</a>
        </nuxt-link>
      </li>
      <li class="nav-item">
        <nuxt-link to="/">
          <a class="nav-link active" href="#">Titan</a>
        </nuxt-link>
      </li>
      <li class="nav-item">
        <nuxt-link to="/">
          <a class="nav-link active" href="#">Chara</a>
        </nuxt-link>
      </li>
    </ul>
    <nuxt />
  </div>
</template>

<style>
body {
  overflow-x: hidden;
}
.b {
  background-color: #35495e;
}
.nav-link {
  color: rgba(238, 149, 66, 0.883);
}
html {
  font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI",
    Roboto, "Helvetica Neue", Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}
</style>
