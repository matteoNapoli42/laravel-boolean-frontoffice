<script>
export default {
  name: "AppHeader",
};
</script>

<template>
  <header>
    <nav class="navbar navbar-expand-sm shadow">
      <div class="container">
        <a class="navbar-brand" href="#">BoolBar</a>
        <button
          class="navbar-toggler d-lg-none"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#collapsibleNavId"
          aria-controls="collapsibleNavId"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="collapsibleNavId">
          <ul class="navbar-nav me-auto mt-2 mt-lg-0">
            <li class="nav-item">
              <router-link
                class="nav-link"
                active-class="active"
                to="/"
                aria-current="page"
                >Home
                <span class="visually-hidden">(current)</span></router-link
              >
            </li>
            <li class="nav-item">
              <router-link class="nav-link" active-class="active" to="/about"
                >About us</router-link
              >
            </li>
            <li class="nav-item">
              <router-link class="nav-link" active-class="active" to="/contact"
                >Contact us</router-link
              >
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </header>
</template>

<style lang="scss" scoped></style>
