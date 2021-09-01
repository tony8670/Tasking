<template>
  <header>
    <h2>Tasking</h2>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Member</a></li>
        <li><a href="#">EnterPrice</a></li>
      </ul>
    </nav>
    <button class="btn">Sign Up</button>
  </header>
</template>

<script>
export default {
  name: "Navbar"
}
</script>

<style scoped>
li {
  list-style: none;
}

a {
  text-decoration: none;
}

header {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

nav ul {
  display: flex;
}

nav ul li {
  margin: 0 30px;
}

nav ul li a {
  color: gray;
}

.btn {
  padding: 1rem 2.5rem;
  background:#3568CF  ;
  border-radius: 20px;
  border: none;
  color: white;
  font-size: 20px;
}


h2 {
  font-size: 30px;
}
</style>