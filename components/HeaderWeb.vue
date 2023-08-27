<template>
  <header>
    <nav
      class="navbar navbar-expand-lg navbar-light bg-body-tertiary bg-white py-3 fixed-top"
    >
      <div class="container align-items-center">
        <a
          class="navbar-brand color-red"
          href="#"
          style="font-size: 50px; font-weight: bold; padding: 0; color: #f7444e"
          >ALLMART</a
        >
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div id="navbarSupportedContent" class="collapse navbar-collapse">
          <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
            <li class="nav-item me-4">
              <a class="navbar-link active" aria-current="page" href="#"
                >Home</a
              >
            </li>
            <li class="nav-item me-4">
              <a class="navbar-link" href="#">About</a>
            </li>
            <li class="nav-item me-4">
              <a class="navbar-link" href="#">Shop</a>
            </li>
            <li class="nav-item me-4">
              <a class="navbar-link" href="#">Contact</a>
            </li>
          </ul>
          <form class="d-flex" role="search">
            <input
              class="form-control me-2 ms-4"
              type="search"
              placeholder="Search"
              aria-label="Search"
            />
            <button class="btn btn-outline-red" type="submit">Search</button>
          </form>
        </div>
      </div>
    </nav>
  </header>
</template>
