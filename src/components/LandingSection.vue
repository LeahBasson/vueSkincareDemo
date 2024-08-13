<template>
    
<div class="container-fluid no-gutters">

    <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
    <div class="carousel-indicators">
      <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
      <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
      <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
    </div>
    <div class="carousel-inner">
        <div class="carousel-item active">
        <div class="overlay"></div>
        <div class="hb-content">
          <h1 class="animate__animated animate__fadeInDown">Welcome to Skin Oasis</h1>
          <p class="animate__animated animate__fadeInUp">Discover the perfect blend of nature and science to nourish your skin. Dive into our oasis and let your skin thrive.</p>
          <button class="hb-button animate__animated animate__fadeInUp">Explore Now</button>
          <div class="hb-bannerLinks animate__animated animate__fadeInUp">
            <a class="lnk text-white" href="mailto:your-email@example.com" alt="outlook icon" target="_blank"><i class="bi bi-envelope"></i></a>
          <a class="lnk text-white" href="https://www.linkedin.com/in/leah-basson-23a4192a0" alt="linkedin icon" target="_blank"><i class="bi bi-linkedin"></i></a>
          <a class="lnk text-white" href="https://github.com/LeahBasson" target="_blank"><i class="bi bi-github"></i></a>
          </div>
        </div>
        <img class="img-fluid" src="https://leahbasson.github.io/MyImages/skincareWebsite/skincareBanner19.png" alt="slideImage" loading="eager">
      </div>
      <div class="carousel-item">
        <div class="overlay"></div>
        <div class="hb-content">
          <h1 class="animate__animated animate__fadeInDown">Experience the Ultimate Hydration and Glow</h1>
          <p class="animate__animated animate__fadeInUp">Discover our range of skin masks designed for every skin type.</p>
          <button class="hb-button animate__animated animate__fadeInUp">Shop Now</button>
          <div class="hb-bannerLinks animate__animated animate__fadeInUp">
            <a class="lnk text-white" href="mailto:your-email@example.com" alt="outlook icon" target="_blank"><i class="bi bi-envelope"></i></a>
          <a class="lnk text-white" href="https://www.linkedin.com/in/leah-basson-23a4192a0" alt="linkedin icon" target="_blank"><i class="bi bi-linkedin"></i></a>
          <a class="lnk text-white" href="https://github.com/LeahBasson" target="_blank"><i class="bi bi-github"></i></a>
          </div>
        </div>
        <img class="img-fluid" src="https://leahbasson.github.io/MyImages/skincareWebsite/skincareBanner3.jpg" alt="slideImage" loading="eager">
      </div>
      
      <div class="carousel-item">
        <div class="overlay"></div>
        <div class="hb-content">
          <h1 class="animate__animated animate__fadeInDown">Nourish Your Skin Naturally</h1>
          <p class="animate__animated animate__fadeInUp">Say goodbye to dryness and hello to lasting hydration. </p>
          <button class="hb-button animate__animated animate__fadeInUp">Shop Now</button>
          <div class="hb-bannerLinks animate__animated animate__fadeInUp">
            <a class="lnk text-white" href="mailto:your-email@example.com" alt="outlook icon" target="_blank"><i class="bi bi-envelope"></i></a>
          <a class="lnk text-white" href="https://www.linkedin.com/in/leah-basson-23a4192a0" alt="linkedin icon" target="_blank"><i class="bi bi-linkedin"></i></a>
          <a class="lnk text-white" href="https://github.com/LeahBasson" target="_blank"><i class="bi bi-github"></i></a>
          </div>
        </div>
        <img class="img-fluid" src="https://leahbasson.github.io/MyImages/skincareWebsite/skincareBanner22.png" alt="slideImage" loading="eager">
      </div>
    </div>
    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div> 

</div>
    

      
</template>

<style>
.container-fluid.no-gutters {
    padding: 0;
    margin: 0;
}

.carousel-inner{
    width: 100%;
}

img[alt='slideImage']{
    width: 100%;
    height: 82vh;
}

.overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.6); 
    z-index: 1;
}

.hb-content{
    position: absolute;
    top: 10rem;
    left: 28rem;
    width: 40rem;
    z-index: 1;
}

.hb-content h1{
    color: var(--secondary);
    font-size: 2.6rem;
    text-align: center;
    font-family: "Montserrat", sans-serif;
    font-weight: 600;
}

.hb-content p{
    color: var(--secondary);
    text-align: center;
    font-size: 1.2rem;
    font-family: "Montserrat", sans-serif;
}

.hb-button{
    padding: 0.5rem 2rem;
    background-color: var(--alternative);
    border: 1px solid var(--primary);
    border-radius: 0.5rem;
    font-family: "Montserrat", sans-serif;
    font-weight: bold;
    margin-top: 1rem;
}

.hb-button:hover{
    transition: 2s;
    background-color: var(--awesome);
}

.hb-bannerLinks{
   display: flex;
   justify-content: space-between;
   width: 6rem;
   margin:auto;
   margin-top: 1.3rem;
   font-size: 1.3rem;
}

</style>