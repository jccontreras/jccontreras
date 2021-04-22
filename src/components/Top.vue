<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <router-link class="nav-link" :to="{name: 'home'}">
      <img src="@/assets/mylogo.png" style="max-height: 50px; max-width: 80px">
    </router-link>
    <button class="navbar-toggler" type="button" data-toggle="collapse"
            data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown"
            aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNavDropdown">
      <ul class="navbar-nav">
        <li class="nav-item active">
          <router-link class="nav-link linkcolor" :to="{name: 'about'}">
            About me
          </router-link>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Features</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Pricing</a>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'Top',
};
</script>
