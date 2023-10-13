<template>
  <div class="container">
    <div id="blank"></div>
    <div id="blank"></div>
    <div id="avatar">
      <a href="#"><img src="src/assets/Avatar.jpg" class="avatar" /></a>
      <a href="#" class="avatar"><h2>Dabi</h2></a>
    </div>
    <div id="blank"></div>
    <div id="blank"></div>
    <div id="like">
      <a href="#">
        <i class="fa-solid fa-heart fa-2xl" style="color: red"></i>
        <p>9,999 <br>ถูกใจ</p></a>
    </div>
    <div id="note">
      <a href="#">
        <i class="fa-regular fa-note-sticky fa-2xl" style="color: #fbfbfb"></i>
        <p>37<br>โน๊ตที่เขียน</p></a>
    </div>
    <div id="course">
      <a href="#">
        <i class="fa-solid fa-book fa-2xl" style="color: #fbfbfb"></i>
        <p>25 <br>หลักสูตร</p></a>
    </div>
    <div id="blank"></div>
    <div id="blank"></div>
  </div>
  <div class="container2">
    <div class="btn">
      <button class="wishlist">Wishlist</button>
    </div>
  </div>
  
</template>

<style scoped>
.container {
  width: 100%;
  display: flex;
  align-content: center;
  justify-content: center;
  padding: 10px;
  height: 175px;
}
.container div {
  align-items: center;
  margin: 20px;
  width: 100%;
}
.avatar {
  float: left;
  width: 125%;
  border-radius: 100%;
}
#avatar:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
  transition: .5s;
}
p {
  text-align: center;
  font-weight: bold;
}
#like,
#note,
#course {
  text-align: center;
}
a:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
  transition: .5s;
}
h2 {
  font-size: 28px;
  text-align: center;
  font-weight: bold;
}
.like {
  width: 50px;
}
button.wishlist {
  float: right;
  margin-right: 295px;
  padding: 5px 150px;
}
button:hover {
  filter: drop-shadow(0 0 25px #646cffaa);
  transition: .5s;
}
</style>


