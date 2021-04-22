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
        <li class="nav-item">
          <router-link class="nav-link linkcolor" :to="{name: 'about'}">
            About me
          </router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link linkcolor" :to="{name: 'myprojects'}">
            My Projects
          </router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link linkcolor" :to="{name: 'contactme'}">
            Contact me
          </router-link>
        </li>
      </ul>
    </div>
    <div style="float: right;">
      <a href="https://github.com/jccontreras" target="_blank">
        <img src="@/assets/github.png" style="max-height: 30px; max-width: 30px">
      </a>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'Top',
};
</script>
