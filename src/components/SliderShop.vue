<template>
    <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="carousel">
      <div class="carousel-indicators">
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
      </div>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="https://mir-s3-cdn-cf.behance.net/project_modules/max_1200/e7d64b112986373.601ed39c862a6.png" class="d-block w-100 h-100" alt="...">
        </div>
        <div class="carousel-item">
          <img src="https://thietke6d.com/wp-content/uploads/2021/03/Mau-banner-quang-cao-dep-1.png" class="d-block w-100 h-100" alt="...">
        </div>
        <div class="carousel-item">
          <img src="https://mona.media/wp-content/uploads/2021/06/banner-giay.png" class="d-block w-100 h-100" alt="...">
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
    </template>
    <style scoped>
        .carousel-item{
            height: 600px;
        }
    </style>