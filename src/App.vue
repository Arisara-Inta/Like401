<template>
  <div id="app">
    <img class="rounded-circle" src="./assets/bts.jpg" width="50%" />
    <br><br><br>
    <HelloWorld msg="BTS_BANGTAN"   />
    <br>
    <hr />
    <br><br><br>
    <div class="row">
      <div class="col">
        <img class="rounded border border-dark" src="./assets/bangtan.jpg" width="60%" />
        <br />
        <br />
        <coun />
      </div>
      <div class="col">
        <img class="rounded border border-dark" src="./assets/RM.jpg" width="60%" />
        <br />
        <br />
        <coun />
      </div>
      <div class="col">
        <img class="rounded border border-dark" src="./assets/bangtan-boy.jpg" width="60%" />
        <br />
        <br />
        <coun />
      </div>
    </div>
    <div class="row">
      <div class="col">
        <img class="rounded border border-dark" src="./assets/v.jpg" width="60%" />
        <br />
        <br />
        <coun />
      </div>
      <div class="col">
        <img class="rounded border border-dark" src="./assets/jungkook.jpg" width="60%" />
        <br />
        <br />
        <coun />
      </div>
      <div class="col">
        <img class="rounded border border-dark" src="./assets/jimin.jpg" width="60%" />
        <br />
        <br />
        <coun />
      </div>
    </div>
    <div class="row">
      <div class="col">
        <img class="rounded border border-dark" src="./assets/j-hope.jpg" width="60%" />
        <br />
        <br />
        <coun />
      </div>
      <div class="col">
        <img class="rounded border border-dark" src="./assets/suga.jpg" width="60%" />
        <br />
        <br />
        <coun />
      </div>
      <div class="col">
        <img class="rounded border border-dark" src="./assets/jin.jpg" width="60%" />
        <br />
        <br />
        <coun />
      </div> 
    </div>
    <br>
    <hr />
    <br><br><br>
    <div class="row">
    <br><hr /><br><br><br><br><br>
      <div class="col">
        
        <fonts />
        <hr />
        <div class="row-12">
          Name
          <input type="text" v-model="name" />
          Code
          <input type="number" v-model="code" />
          GPA
          <input type="number" v-model="gpa" step="0.1" />
          <br />
          <br />
        </div>
        <div class="row-12">Present : Name {{ชื่อ}} / Code {{รหัสนักศึกษา}} / GPA {{เกรด}}</div>
        <br />
        <br />
      </div>
    </div>
    <footer class="my-5 pt-5 text-muted text-center text-small">
        <p class="mb-1">MJU6104101401@mju.ac.th</p>
    </footer>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import coun from "./components/like.vue";
import fonts from "./components/fonts.vue";
export default {
  name: "App",
  components: {
    HelloWorld,
    coun,
    fonts,
  },
  data: function () {
    return {
      total: 0,
      name: "",
      code: "",
      gpa: 0.1,
    };
  },
};
</script>

<style>
#app {
  background-color: #fbc8d4;
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  position: relative;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: black;
}
</style>
