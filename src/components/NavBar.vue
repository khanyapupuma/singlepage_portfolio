<template>
  <nav class="navbar navbar-expand-lg bg-body-tertiary">
  <div class="container-fluid">
    <router-link class="navbar-brand" href="#">
        <img src="https://khanyapupuma.github.io/all-images/all-images/Images/Screenshot 2024-05-07 140213.png" alt="logo" class="img-fluid" loading="lazy">
    </router-link>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <router-link class="nav-link active" aria-current="page" to="/">Home</router-link>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#about">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#resume">Resume</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#project">Project</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#testimonials">Testimonials</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#reachMe">Reach Me</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
</template>

<script>
export default {

}
</script>

<style>

</style>