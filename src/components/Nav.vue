<template>
    <nav class="navbar navbar-expand-lg">
        <div class="container-fluid">
          <a class="navbar-brand" href="index.html"><img class="img-fluid" src="https://leahbasson.github.io/MyImages/skincareWebsite/skincareLogo2.gif" alt="logo" loading="eager"></a>
          <button class="navbar-toggler" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasNavbar" aria-controls="offcanvasNavbar" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="offcanvas offcanvas-end" tabindex="-1" id="offcanvasNavbar" aria-labelledby="offcanvasNavbarLabel">
            <div class="offcanvas-header">
              <h5 class="offcanvas-title" id="offcanvasNavbarLabel"><img class="img-fluid" src="https://leahbasson.github.io/MyImages/skincareWebsite/skincareLogo2.gif" alt="logo" loading="eager"></h5>
              <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
            </div>
            
            <div class="offcanvas-body">
              <ul class="navbar-nav justify-content-center flex-grow-1 pe-3">
                <li class="nav-item mt-2">
                  <a class="nav-link" aria-current="page" href="#home">Home</a>
                </li>
                <li class="nav-item dropdown mt-2">
                    <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                     Collection
                    </a>
                    <ul class="dropdown-menu">
                      <li><a class="dropdown-item" href="#new">New</a></li>
                      <li><a class="dropdown-item" href="#all">Shop All</a></li>
                    </ul>
                  </li>
                  <li class="nav-item dropdown mt-2">
                    <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                     Category
                    </a>
                    <ul class="dropdown-menu">
                      <li><a class="dropdown-item" href="#masks">Masks</a></li>
                      <li><a class="dropdown-item" href="#moisturizer">Moisturizer</a></li>
                    </ul>
                  </li>
                  <li class="nav-item dropdown mt-2">
                    <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                     Skin Type
                    </a>
                    <ul class="dropdown-menu">
                      <li><a class="dropdown-item" href="#oily">Oily</a></li>
                      <li><a class="dropdown-item" href="#dry">Dry</a></li>
                      <li><a class="dropdown-item" href="#combination">Combination</a></li>
                    </ul>
                  </li>
                  <li class="nav-item dropdown mt-2">
                    <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                     Skin Concern
                    </a>
                    <ul class="dropdown-menu">
                      <li><a class="dropdown-item" href="#sensitive">Sensitive</a></li>
                      <li><a class="dropdown-item" href="#wrinkles">Wrinkles</a></li>
                    </ul>
                  </li>
                  <li class="nav-item mt-2">
                    <a class="nav-link" aria-current="page" href="#ourStory">Our Story</a>
                  </li>
                  <li class="nav-item mt-2">
                    <a class="nav-link" aria-current="page" href="#contact">Contact</a>
                  </li>
              </ul>
              

              <ul class="navbar-nav justify-content-end">
                <li class="nav-item">
                    <a class="nav-link" aria-current="page" href="#account"><i class="bi bi-person"></i></a>
                  </li>
                <li class="nav-item">
                  <a class="nav-link" aria-current="page" href="#bag"><i class="bi bi-bag"></i></a>
                </li>
              </ul>
            </div>
    
          </div>
        </div>
      </nav>
</template>

<script>
    export default {
        name: "NavComp"    
    }   
</script>

<style scoped>
img[alt='logo']{
    width: 15rem;
    object-fit: cover;
    object-position: center;
    transition: all .5s;
}

img[alt='logo']:hover{
  transform: scale(1.1);
}

.nav-link{
    color: black;
    font-family: "Poppins", sans-serif;
    font-size: 1rem;
}

.nav-link:hover{
    color: #5D7599; 
}

.navbar{
    transition: all 0.5s;
}

.nav-link i{
    font-size: 1.5rem;
}

:is(.dropdown-item:active){
    background-color: #5D7599;
}

@media (width < 999px)
{ 
  .navbar-nav{
    text-align: left;
    margin-left: 1rem;
  }

    img[alt='logo']{
      width: 12rem;
    }
}

</style>