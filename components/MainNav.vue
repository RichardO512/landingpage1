<template>
  <header class="navbar navbar-expand-lg navbar-light bg-light">
    <a class="logo-circle navbar-brand" href="#">
      <img src="../assets/Untitle.png" alt="" />
    </a>

    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarNavDropdown"
      aria-controls="navbarNavDropdown"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>
    <div id="navbarNavDropdown" class="collapse navbar-collapse">
      <ul class="navbar-nav">
        <li class="nav-item active">
          <a class="nav-link" href="#">Home </a>
          <!-- product dropdown -->
        </li>
        <li class="nav-item dropdown">
          <a
            id="navbarDropdownMenuLink"
            class="nav-link dropdown-toggle"
            href="#"
            data-toggle="dropdown"
            aria-haspopup="true"
            aria-expanded="false"
          >
            Products
          </a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
            <a class="dropdown-item" href="#">Product 1</a>
            <a class="dropdown-item" href="#">Product 2</a>
            <a class="dropdown-item" href="#">Product 3</a>
          </div>
        </li>
        <li class="nav-item dropdown">
          <a
            id="navbarDropdownMenuLink"
            class="nav-link dropdown-toggle"
            href="#"
            data-toggle="dropdown"
            aria-haspopup="true"
            aria-expanded="false"
          >
            Resources
          </a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
            <a class="dropdown-item" href="#">Resource 1</a>
            <a class="dropdown-item" href="#">Resource 2</a>
            <a class="dropdown-item" href="#">Resource 3</a>
          </div>
        </li>

        <li class="nav-item">
          <a class="nav-link" href="#">Pricing</a>
        </li>
      </ul>
    </div>
    <button type="button" class="btn btn-circle p-0">
      <img src="../assets/Avatar-3.png" alt="" />
    </button>
  </header>
</template>
<script>
export default {
  name: 'MainNav',
}
</script>
<style scoped src="../style/MainNav.css"></style>
