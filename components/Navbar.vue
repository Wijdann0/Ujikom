<template>
  <div>
    <!-- Top Bar -->
    <div class="bg-success text-white pt-2 py-1 justify-content-between align-items-center px-3">
      <marquee class="flex-grow-1">
        Website Sekolah SMK Negeri 4 Tasikmalaya (Untuk Ujikom)
      </marquee>
    </div>
    <div class="bg-white px-2 text-end pt-2">
      <span>04 Desember 2025</span>
    </div>
    <hr class="shadow-sm">

    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-white shadow-sm">
      <div class="container-fluid">
        <a class="navbar-brand d-flex align-items-center" href="/">
          <img src="../assets/image/logoSMK.png" alt="Logo" width="35" class="me-3" />
          <span class="fw-bolder">SMK Negeri 4 Tasikmalaya</span>
        </a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarNav"
          aria-controls="navbarNav"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ms-auto">
            <li class="nav-item">
              <nuxt-link to="/" class="nav-link active" aria-current="page">HOME</nuxt-link>
            </li>

            <li>
              <nuxt-link to="/profile" class="nav-link">PROFILE</nuxt-link>
            </li>

            <li>
              <nuxt-link to="/saranaPrasarana" class="nav-link">SARPRAS</nuxt-link>
            </li>

            <li>
              <nuxt-link to="/ekstrakurikuler" class="nav-link">EKSTRAKURIKULER</nuxt-link>
            </li>
            <li>
              <nuxt-link to="/gallery" class="nav-link">GALLERY</nuxt-link>
            </li>

            
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>


<style scoped>
marquee {
  font-size: 14px;
}
.navbar-brand img {
  border-radius: 50%;
}
.nav-link {
  transition: color 0.3s ease;
}
.nav-link:hover {
  color: #4caf50;
}

/* Navbar Styles */
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #ffffff;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  padding: 10px 20px;
}

.navbar .logo {
  font-size: 20px;
  font-weight: bold;
}

.navbar ul {
  list-style: none;
  gap: 20px;
  margin: 0;
  padding: 0;
}

.navbar ul li {
  position: relative;
}

.navbar ul li a {
  text-decoration: none;
  color: #333;
  padding: 10px 15px;
  display: block;
  font-size: 16px;
}

/* Dropdown Menu */
.dropdown-menu {
  display: none;
  position: absolute;
  top: 100%;
  left: 0;
  background-color: #ffffff;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
  z-index: 100;
  min-width: 200px;
}

.dropdown-menu li {
  width: 100%;
}

.dropdown-menu li a {
  padding: 10px;
}

.dropdown:hover .dropdown-menu {
  display: block;
}
</style>
