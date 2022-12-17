<template>
  <div class="header">
    <img alt="logo" src="../assets/logo.png" />
  </div>
  <nav class="navbar">
    <div class="links">
      <a href="/">Home</a>
      <a href="/blog">Blog</a>
      <a href="/contact">Contact Us</a>
    </div>
  </nav>
</template>

<style scoped>
.header img {
  width: 20%;
  margin: 0 auto;
}
.header {
  padding: 20px;
  display: flex;
  max-width: 75%;
  margin: 0 auto;
  justify-content: center;
}
.navbar {
  padding: 20px;
  display: flex;
  align-items: center;
  max-width: 75%;
  margin: 0 auto;
  border-top: 1px solid #f2f2f2;
  border-bottom: 1px solid #f2f2f2;
}
.navbar h1 {
  color: #000;
}
.navbar .links {
  margin: auto;
}
.navbar a {
  margin-left: 16px;
  text-decoration: none;
  padding: 6px;
  color: #6f42c1;
}
.navbar a:hover {
  color: white;
  background-color: #75d0c1;
  border-radius: 5px;
}
</style>