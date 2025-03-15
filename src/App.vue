<template>
  <div class="container-fluid vh-100"> 
    <div class="row">
      <nav class="navbar navbar-expand-lg navbar-light bg-info">
        <a class="navbar-brand mr-10" href="#">Puede Education</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item active">
              <a class="nav-link" href="#"> Landing <span class="sr-only">(current)</span></a>
            </li>
          </ul>
        </div>
      </nav>
    </div>

    <div class="row d-flex">
      <div class="col-7"> 
        <FoodDisplay/>
      </div>
      <div class="col-5 justify-content-center">
        <h1 class="text-center"> User Login </h1>
        <form>
          <div class="form-group">
            <label for="exampleInputEmail1">Email address</label>
            <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Enter email">
            <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
          </div>
          <div class="form-group">
            <label for="exampleInputPassword1">Password</label>
            <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Password">
          </div>
          <div class="form-group form-check">
            <input type="checkbox" class="form-check-input" id="exampleCheck1">
            <label class="form-check-label" for="exampleCheck1">Check me out</label>
          </div>
          <button type="submit" class="btn btn-primary">Submit</button>
        </form>
      </div>
    </div>

    <div class = "row">
      <div class = "col-6 justify-content-start">
        <h1 class="font-weight-bold text-monospace"> Your Body Deserve Healthy Food </h1>
        <p class="font-weight-normal text-monospace"> Bon Apetit </p>
      </div>
    </div>

    <div class = "row">
      <div class= "col-12">
        <p class = "text-muted text-end"> Copyright Puede Education </p>
      </div>
    </div>
  </div>
</template>

<script>
import FoodDisplay from './components/FoodDisplay.vue';

export default {
  name: 'App',
  components: {
    FoodDisplay,
  }
};
</script>