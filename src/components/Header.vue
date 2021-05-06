<template>
  <!-- Header -->

  <header class="header trans_300">

    <!-- Top Navigation -->

    <div class="top_nav">
      <div class="container">
        <div class="row">
          <div class="col-md-6">
            <div class="top_nav_left">Envío gratis en compras mayores a Q300 en todo el país</div>
          </div>
          <div class="col-md-6 text-right">
            <div class="top_nav_right">
              <ul class="top_nav_menu">

                <!-- Currency / Language / My Account -->

                <li class="currency">
                  <a href="#">
                    Q.
                  </a>
                </li>
                <li class="language">
                  <a href="#">
                    Español
                  </a>
                </li>
                <li class="account">
                  <a href="#">
                    Mi Cuenta
                    <i class="fa fa-angle-down"></i>
                  </a>
                  <ul class="account_selection">
                    <li><a href="./login.html"><i class="fa fa-sign-in" aria-hidden="true"></i>Ingresar</a></li>
                    <li><a href="./registro.html"><i class="fa fa-user-plus" aria-hidden="true"></i>Crear</a></li>
                  </ul>

                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Main Navigation -->

    <div class="main_nav_container">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-right">
            <div class="logo_container">
              <a href="#">MEGA<span>Gangas GGT</span></a>
            </div>
            <nav class="navbar">
              <!-- <div id="nav">
   <router-link to="/">Home</router-link> |
   <router-link to="/about">About</router-link>
 </div>
 <router-view/> -->
              <ul class="navbar_menu">
                <li><a><router-link to="/">Inicio</router-link></a></li>
                <li><a><router-link to="/login">Login</router-link></a></li>
                <li><a href="./contact.html">Contacto</a></li>
              </ul>
              <router-view/>
              <ul class="navbar_user">
                <li class="checkout">
                  <a href="#">
                    <i class="fa fa-shopping-cart" aria-hidden="true"></i>
                    <span id="checkout_items" class="checkout_items">0</span>
                  </a>
                </li>
              </ul>
              <div class="hamburger_container">
                <i class="fa fa-bars" aria-hidden="true"></i>
              </div>
            </nav>
          </div>
        </div>
      </div>
    </div>

  </header>
</template>

<script>
export default {
name: "Header.vue"
}
</script>

<style scoped>

</style>