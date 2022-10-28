<template>
  <div class="home">

    <div class="home-wrapper">
      <div class="left">
        <div class="shape"></div>
        <img src="../assets/mc_khan_edited.jpg" alt="">
      </div>
      <div class="right">
        <h1>Hi i'm <span>Axtamov Amirxan</span> A Web Developer</h1>
        <p>I am a junior web developer I am shas vue. Ipsum dolore atque ducimus sed similique pariatur
          dolores sit nulla adipisci! Sit asperiores necessitatibus modi alias officia numquam nemo eligendi veritatis
          quaerat.</p>
        <button>Dowland Cv</button>
      </div>
    </div>

  </div>
</template>

<script>
export default {
  name: 'Home',
}
</script>
<style scoped>
.home {
  background: #191D2B;
  height: 869px;
  width: 100%;
  display: flex;
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}

.home-wrapper {
  width: 90%;
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin: auto;
}

.left {
  /* background-color: red; */
  height: 100%;
  width: 48%;
  display: flex;
  align-items: center;
  justify-content: center;
}
.shape{
    transition: all 0.4s ease-in-out;
    width: 45%;
    height: 89.7%;
    background-color: #27ae60;
    position: absolute;
    top: 100px;
    left: 0;
    z-index: 0;
    clip-path: polygon(0 0, 46% 0, 79% 100%, 0% 100%);

}

.left img {
  height: 780px;
  width: 650px;
  border-radius: 14px;
  transition-duration: .5s;
  filter: grayscale(100%);
}
.left img:hover{
  filter: grayscale(0%);
}


.right {
  /* background-color: blue; */
  height: 100%;
  width: 48%;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
}

.right h1 {
  color: white;
  font-size: 3rem;
  margin-bottom: 20px;
  width: 80%;
}

.right h1 span {
  color: #27ae60;
}

.right p {
  color: white;
  line-height: 30px;
  font-size: 20px;
  font-weight: 700;
  margin-bottom: 30px;
  width: 85%;
}

.right button {
  border-radius: 30px;
  font-weight: 700;
  border: 2px solid #27ae60;
  background: transparent;
  color: white;
  font-size: 20px;
  cursor: pointer;
  width: 220px;
  height: 60px;
  /* padding: 20px 40px; */
}

</style>
