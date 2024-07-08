<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#">My Nuxt App</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
        aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <nuxt-link to="/" class="nav-link" exact>Home</nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link to="/about" class="nav-link">About</nuxt-link>
          </li>
          <!-- Add more links as needed -->
        </ul>
      </div>
    </div>
  </nav>
  <div class="container">
    <div class="card">
    <img src="#" class="card-img-top" alt="Card image cap">
    <div class="card-body">
      <h5 class="card-title">title</h5>
      <p class="card-text">description</p>
      <a href="#" class="btn btn-primary">Go somewhere</a>
    </div>
  </div>
  <div class="card">
    <img src="#" class="card-img-top" alt="Card image cap">
    <div class="card-body">
      <h5 class="card-title">title</h5>
      <p class="card-text">description</p>
      <a href="#" class="btn btn-primary">Go somewhere</a>
    </div>
  </div>
    <h1 class="display-4">Hello, Bootstrap in Nuxt.js!</h1>
    <button class="btn btn-primary">Primary Button</button>
  </div>
</template>
