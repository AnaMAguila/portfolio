<template>
  <div class="container-fluid p-0">
    <!-- MENU -->
    <div>
      <Nav />
    </div>   

    <!-- HOME -->
    <p id="home" class="p-3"></p>
    <div class="mt-5">
      <div class="container-fluid">
        <div class="row">
          <Home />
        </div>
      </div>

      <!-- WORKS -->
      <p id="works"></p>
      <div class="row mt-2 mt-md-4 p-3 works">
        <div class="col-12 text-center fs-2 fw-bolder text-white mt-3 mb-3">
          WORKS
        </div>
        <div class="col-12">
          <Works />
        </div>
      </div>

      <!-- ABOUT -->
      <p id="about"></p>
      <div class="row p-3">
        <div class="col-12 text-center fs-2 fw-bolder mt-3 mb-3">ABOUT</div>
        <div class="col-12">
          <About />
        </div>
      </div>

      <!-- CONTACT -->
      <p id="contact"></p>
      <div class="row p-3 contact">
        <div class="col-12 text-center fs-2 fw-bolder text-white mt-3 mb-3">
          CONTACT
        </div>
        <div class="col-12">
          <Contact />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Nav from "./components/Nav.vue"
import Works from "./components/Works.vue";
import About from "./components/About.vue";
import Contact from "./components/Contact.vue";
import Home from "./components/Home.vue";

export default {
  name: "App",
  created () {
            document.title = "Ana Mª Águila";
  },
  components: {
    Nav,
    Home,
    Works,
    About,
    Contact,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,400;0,700;0,800;0,900;1,700;1,800;1,900&display=swap");

* {
  font-family: "Montserrat", sans-serif;
  padding: 0;
  margin: 0;
}

.works {
  background-color: #EB455F;
}

.contact {
  background-color: #00115f;
}
</style>