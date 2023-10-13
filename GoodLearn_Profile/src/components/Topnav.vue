<template>
  <nav>
    <!-- <label class="logo"><img src="src/assets/logo.svg" /></label> -->
    <label for="type" class="textnav">บัญชี</label>
    <input type="checkbox" id="check" />
    <label for="check" class="checkbtn">
      <i class="fas fa-bars"></i>
    </label>
    <ul>
      <li>
        <a href="#"
          ><i
            class="fa-solid fa-cart-shopping fa-2xl"
            style="color: #fbfbfb"
          ></i
        ></a>
      </li>
    </ul>
    <ul>
      <li>
        <a href="#"
          ><i class="fa-regular fa-heart fa-2xl" style="color: #fbfbfb"></i
        ></a>
      </li>
    </ul>
    <ul>
      <li>
        <a href="#"
          ><i class="fa-regular fa-bell fa-2xl" style="color: #fbfbfb"></i
        ></a>
      </li>
    </ul>
  </nav>
</template>

<style scoped>
nav {
  height: 80px;
  width: 100%;
  margin-top: 2%;
  list-style-type: none;
}

label.logo {
  margin-left: 50px;
  cursor: pointer;
}

label.textnav {
  font-size: 35px;
  line-height: 80px;
  padding: 0 100px;
  font-weight: bold;
  cursor: pointer;
}

label.textnav:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
  transition: .5s;
  color: #6564CA;
}

nav ul {
  float: right;
  margin-right: 20px;
}

nav ul li {
  display: inline-block;
  line-height: 80px;
  margin: 0 5px;
}

nav ul li a {
  text-transform: uppercase;
}

ul li {
  width: 20px;
}

a:hover {
  color: #53ffac;
  transition: 0.5s;
}

.checkbtn {
  float: right;
  line-height: 80px;
  margin-right: 40px;
  cursor: pointer;
  display: none;
}

#check {
  display: none;
}

li:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
  transition: .5s;
}

.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
  transition: .5s;
}

@media (max-width: 952px) {
  label.textnav {
    font-size: 30px;
    padding-left: 50px;
  }
  nav ul li a {
    font-size: 16px;
  }
}

@media (max-width: 858px) {
  .checkbtn {
    display: block;
  }
  ul {
    position: fixed;
    width: 50%;
    height: 100vh;
    background: #1a1920;
    top: 80px;
    left: -100%;
    text-align: center;
    transition: all 0.5s;
  }
  nav ul li {
    display: block;
    margin: 50px 0;
    line-height: 30px;
  }
  nav ul li a {
    font-size: 20px;
  }
  a:hover {
    background: none;
    color: #53ffac;
  }
  #check:checked ~ ul {
    left: 0;
  }
}
</style>
