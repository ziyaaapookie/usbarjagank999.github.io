
<template>
    <div>
       
  <header class="header-all">
    <div class="container">
      <!-- Navbar -->
      <div class="navbar">
        <div class="logo">
          <h1>PT. USBARJA TEKNIK MULIA</h1>
        </div>
        <ul class="menu">
          <li class="menu-item">
            <i class="fa-solid fa-house"></i>
            <router-link to="/">Home</router-link>
          </li>
          <li class="menu-item">
            <i class="fa-solid fa-address-card"></i>
            <router-link to="/about">About Us</router-link>
          </li>
          <li class="menu-item">
            <i class="fa-solid fa-house-circle-check"></i>
            <router-link to="/product">Product</router-link>
          </li>
          <li class="menu-item">
            <i class="fa-solid fa-gear"></i>
            <router-link to="/services">Services</router-link>
          </li>
          <li class="menu-item">
            <i class="fa-solid fa-thumbs-up"></i>
            <router-link to="/feedback">Feedback</router-link>
          </li>
          <li class="menu-item">
            <i class="fa-solid fa-thumbs-up"></i>
            <router-link to="/team">Team</router-link>
          </li>
        </ul>
        <div class="our-app">
          <router-link to="/login" class="our-app-btn">Login</router-link>
          <!-- btn hamburger -->
          <button class="hamburger hamburger--spin" type="button">
            <span class="hamburger-box">
              <span class="hamburger-inner"></span>
            </span>
          </button>
        </div>
      </div>

      
    </div>
  </header>



    </div>
   </template>
   <script>
   
   export default {
    name: 'HeaderComponent'
   }
   </script>