<template>
  <div>
    <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
      <ol class="carousel-indicators">
        <li data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active"></li>
        <li data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1"></li>
        <li data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2"></li>
      </ol>
      <div class="carousel-inner">
        <div class="carousel-item active" data-bs-interval="1500">
          <img class="d-block object-fit-cover" src="@/assets/images/beef-yakiniku.jpg" alt="First slide">
          <div class="carousel-caption d-none d-md-block">
            <h5>Sweet and Savory Yakiniku Beef</h5>
          </div>
        </div>
        <div class="carousel-item" data-bs-interval= "1500">
          <img class="d-block object-fit-cover" src="@/assets/images/Cap Jay.jpg" alt="Second slide">
          <div class="carousel-caption d-none d-md-block">
            <h5>Oriental Cap Jay: Authentic Chinese Food</h5>
          </div>
        </div>
        <div class="carousel-item" data-bs-interval="1500">
          <img class="d-block object-fit-cover" src="@/assets/images/Carbonara.jpg" alt="Third slide">
          <div class="carousel-caption d-none d-md-block">
            <h5>Delicious Carbonara: Authentic Italian Dish</h5>
          </div>
        </div>
      </div>
      <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
      </a>
      <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
      </a>
    </div>
  </div>
</template>


<script>
    
    export default {
        name : "FoodDisplay"
    };

</script>