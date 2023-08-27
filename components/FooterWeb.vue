<template>
  <footer>
    <div class="container">
      <div class="row">
        <div class="col-12 col-lg-4">
          <h1 class="logo">ALLMART</h1>
          <p>
            ADDRESS: Mojorejo RT 2/RW 5, Ngerong, Gempol, Pasuruan, Indonesia
          </p>
          <p>TELEPHONE: +62 882 1883 2453</p>
          <p>EMAIL: bayuhadi863@gmail.com</p>
        </div>
        <div class="col-12 col-lg-2">
          <h1>MENU</h1>
          <ul>
            <li><a href="">Home</a></li>
            <li><a href="">About</a></li>
            <li><a href="">Shop</a></li>
            <li><a href="">Contact</a></li>
          </ul>
        </div>
        <div class="col-12 col-lg-2">
          <h1>ACCOUNT</h1>
          <ul>
            <li><a href="">Account</a></li>
            <li><a href="">Login</a></li>
            <li><a href="">Register</a></li>
          </ul>
        </div>
        <div class="col-12 col-lg-4">
          <h1>NEWSLETTER</h1>
          <p>Subscribe by our newsletter and get update protidin.</p>
          <form class="d-flex" role="search">
            <input
              class="form-control me-2"
              type="search"
              placeholder="Search"
              aria-label="Search"
            />
            <button class="btn btn-outline-red" type="submit">Search</button>
          </form>
        </div>
      </div>
    </div>
    <div class="text-center mt-5 py-5 copyright">
      &copy; 2023 AllMart. All right reserved.
    </div>
  </footer>
</template>

<style scoped>
footer {
  background: #222222;
  color: #e9e9e9;
  padding-top: 4rem;
}
h1 {
  font-size: 1.7rem;
  font-weight: 600;
  margin-bottom: 1rem;
}
.logo {
  color: #f7444e;
}
ul {
  padding: 0;
}
li {
  list-style-type: none;
  margin-bottom: 10px;
}
p,
a {
  font-size: 1.1rem;
}
a {
  text-decoration: none;
  color: #e9e9e9;
  transition: all 0.2s;
}
a:hover {
  text-decoration: none;
  color: #f7444e;
}
.copyright {
  border-top: 1px solid rgb(85, 85, 85);
}
</style>
