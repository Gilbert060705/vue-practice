<template>
  <div class="container-fluid vh-100"> 
    <div class="row">
      <NavBar/>
    </div>

    <div class="row">
      <div class="col-6"> 
        <FoodDisplay/>
      </div>
      <div class="col-6">
        <h1 class="font-weight-bold"> Login Here </h1>
        <input type="text" placeholder = "Username"/> <br/> 
        <input type="text" placeholder = "Password"/>
      </div>
    </div>

    <div class = "row">
      <div class = "col-6 justify-content-start">
        <h1 class="font-weight-bold text-monospace"> Your Body Deserve Healthy Food </h1>
        <p class="font-weight-normal text-monospace"> Bon Apetit </p>
      </div>
    </div>

    <div class = "row">
      <p class = "text-muted"> Copyright Puede Education </p>
    </div>
  </div>
</template>

<script>
import FoodDisplay from './components/FoodDisplay.vue';
import NavBar from './components/NavBar.vue';

export default {
  name: 'App',
  components: {
    FoodDisplay,
    NavBar
  }
};
</script>