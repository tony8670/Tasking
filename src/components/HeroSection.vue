<template>
  <div class="container">
  <div class="left">
    <h1>Manage Your <span>Task</span> Easily</h1>
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Animi corporis dolore itaque libero mollitia odio quod,
      sed!</p>
    <div class="bottom">
      <button class="btn">Learn more</button>
      <div class="video">
        <img src="https://icons.iconarchive.com/icons/iconsmind/outline/512/Video-5-icon.png" alt="video"/>
        <h3>Watch Video</h3>
      </div>
    </div>
  </div>
  <div class="right">
    <img src="/src/pexels-monstera-5384429-removebg-preview.png" alt="">
  </div>
  </div>
</template>

<script>
export default {
  name: "HeroSection"
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@500;700&display=swap');

.container{
  display: flex;
}
.left {
  width: 50%;
}

.left h1 {
  font-family: 'Poppins', sans-serif;
  font-size: 6rem;
  font-weight: 500;
  cursor: pointer;
}

.left h1 span {
  font-weight: 700;
  text-decoration: underline;
}

.left p {
  color: #AAAAAB;
}

.right {
  width: 50%;
  display: grid;
  place-items: center;
}
.btn {
  padding: 1rem 2.5rem;
  background: #3568CF;
  border-radius: 20px;
  border: none;
  color: white;
  font-size: 20px;
  margin-right: 20px;
}

.bottom {
  display: flex;
  align-items: center;
}

.video {
  display: flex;
}
.video img {
  max-width: 70px;
  margin-right: 10px;
}



</style>