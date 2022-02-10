<template>
<div>
  <b-navbar toggleable="lg" type="dark" variant="info">
    <b-navbar-brand href="#">REDIS_cover Travel!</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <NuxtLink to="/about">About</NuxtLink>
      </b-navbar-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>

<b-img height="300px" width="550px" center src="~/assets/header.jpg" alt="Header image">
</b-img>



</div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
