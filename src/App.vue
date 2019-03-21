<template>
  <div id="app">

      <b-navbar toggleable="lg" type="dark" variant="dark">
            <b-navbar-brand href="#">Person administrator</b-navbar-brand>
            <b-navbar-toggle target="nav_text_collapse" />

            <b-collapse is-nav id="nav_text_collapse">
                <b-navbar-nav class="ml-auto">
                    <b-nav-item to="/">Home</b-nav-item>
                    <b-nav-item to="/about">About</b-nav-item>
                </b-navbar-nav>
            </b-collapse>
      </b-navbar>
    <router-view/>
  </div>
</template>

<style>
</style>
