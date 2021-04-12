<template>
  <div id="wrapper">
    <nav class="navbar is-dark">
      <div class="navbar-brand">
        <router-link to="/" class="navbar-item"> <strong>E commerce</strong> </router-link>

        <a class="navbar-burger" arial-label="menu" aria-expanded="false" data-target="navbar-menu">
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
        </a>
      </div>
      <div class="navbar-menu" id="navbar-menu">
        <div class="navbar-end">
          <router-link to="/summer" class="navbar-item"> Summer</router-link>
          <router-link to="/winter" class="navbar-item"> Winter</router-link>
          
          <div class="navbar-item">
            <div class="buttons">
              <router-link to="/log-in" class="button is-light"> Log in</router-link>
              <router-link to="/cart" class="button is-success"> 
                <span class="icon"><i class="fas fa-shopping-xar"></i>
                  <span>Cart</span>
                </span>
              </router-link>
            </div>
          </div>
        </div>
      </div>
    </nav>

    <section class="section">
      <router-view/>
    </section>

    <footer class="footer">
      <p class="has-text-centered">All Copyright 2021 belong to salmentochitlango@gmail.com</p>
    </footer>
  </div>
</template>

<style lang="scss">
  @import "../node_modules/bulma";
</style>
