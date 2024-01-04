<template>
       <nav class="navbarAdmin navbar navbar-expand-lg">
          <div class="container-fluid p-3 px-3 mx-md-3">
            <div class="judul" style="color:white">
              <h5>Admin Dashboard</h5>
            </div>

            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" 
              data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" 
              aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
        
            <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
              <ul class="navbar-nav">
                <li class="nav-item my-1">
                    <NuxtLink to="/" class="nav-item home mx-4 m-5">Home Page</NuxtLink>
                </li>
                <li class="nav-item">
                  <button @click="toLogin" class="btn btn-danger logout nav-item">Log Out</button>
                </li>
              </ul>
            </div>
          </div>
        </nav>
</template>

<script>
export default {
    methods: {
        toLogin(){
            alert("Anda logout! redirect ke halaman login")
            navigateTo('/login')
        }
    }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,300;0,500;0,700;1,300;1,500;1,700&display=swap');

:root {
    --primary-color:  #73101E;
    --secondary-color: #AB3C41;
    --tertiary-color: #ef5b62;
    --pink: #fcf5f3;
    --main-text-color: #2B2B2B;
}

* {
    font-family: 'Poppins', Arial, sans-serif;
}

/* costumize navbar */

.navbarAdmin {
    background-color: var(--secondary-color) !important;
}

.judul {
  color:white;
}

.home{
    color:white;
}

.home:hover {
    color: var(--pink) !important;
   
    
    transition: color 0.5s ease;
}

.logout {
  background-color: white !important;
  color:var(--secondary-color) !important;
}



#logo {
    cursor: pointer;
    transition: transform 1s ease-in-out;
}

.navbar-toggler{
    border: 0px;
}

.nav-link.active  {
    color: var(--main-text-color) !important;
}


</style>