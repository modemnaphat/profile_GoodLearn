<template>
  <div class="frame">
    <a href="#" class="course"
      ><div class="course">
        <h1 class="c-name">One For All</h1>
        <div class="block1">
          <img src="src/assets/Teacher.png" class="corporate" />
          <h2 class="t-name">All Might<br />U.A. High School</h2>
        </div>
      </div></a
    >

    <div class="container">
      <div id="blank"></div>
      <div id="block2">
        <h2 id="p-text">ความคืบหน้า</h2>
        <h1 id="percent">50%</h1>
        <img src="src/assets/percentagebar.png" class="percent-bar" />
      </div>
      <div id="blank"></div>
      <div id="block3">
        <img src="src/assets/VLine.png" class="verticalline" />
      </div>
      <div id="block4">
        <h2 id="txtb4">การเรียน</h2>
        <h2 id="txtb4">แบบฝึกหัด</h2>
        <h2 id="txtb4">บททดสอบ</h2>
        <h2 id="txtb4">ชิ้นงาน</h2>
      </div>
      <div id="blank"></div>
      <div id="block5">
        <h2 id="txtb5">7% 01/15</h2>
        <h2 id="txtb5">5% 01/20</h2>
        <h2 id="txtb5">5% 01/20</h2>
        <h2 id="txtb5">5% 01/20</h2>
      </div>
    </div>
  </div>
  <div class="slide">
    <a href="#"
      ><i
        class="fa-solid fa-circle-chevron-left fa-2xl"
        id="leftarr"
        style="color: #fbfbfb"
      ></i
    ></a>
    <a href="#"
      ><i
        class="fa-solid fa-circle-chevron-right fa-2xl"
        id="rightarr"
        style="color: #fbfbfb"
      ></i
    ></a>
  </div>
</template>

<style scoped>
.frame {
  background-color: #fbfbfb;
  border-radius: 25px;
  margin-top: 150px;
  width: 100%;
  height: 700px;
}
/*part1*/
.course {
  background-color: #53ffac;
  margin-top: 100px;
  width: 100%;
  height: 325px;
  border-radius: 25px;
}
.course:hover {
  filter: drop-shadow(0 0 10px #42b883aa);
  transition: 0.5s;
  opacity: 0.9;
}
h1.c-name {
  color: #1a1920;
  font-size: 48px;
  padding: 25px 25px;
  margin-left: 50px;
}
h2.t-name {
  color: #1a1920;
  font-size: 30px;
}
.block1 {
  width: 100%;
  display: flex;
}
.block1 div {
  align-items: center;
  margin: 75px;
  width: 100%;
}
img.corporate {
  width: 150px;
  padding: 0 25px;
  margin-left: 50px;
  border-radius: 100%;
}

/*part 2 */
.container {
  display: flex;
  width: 100%;
  height: 325px;
}
.container div {
  margin: 20px;
  width: 100%;
}
#block2 {
  width: 25%;
  float: left;
  align-items: center;
  padding: 5% 0;
  line-height: 10px;
  margin-left: 75px;
}
#block3 {
  float: left;
  width: 1%;
  align-items: center;
  padding: 5% 0;
  line-height: 10px;
}
#block4 {
  width: 25%;
  float: left;
  align-items: center;
  padding: 5% 0;
  line-height: 24px;
  margin-left: 75px;
}
#block5 {
  width: 25%;
  float: left;
  align-items: center;
  padding: 5% 0;
  line-height: 24px;
  margin-left: 75px;
}
div#blank {
  width: 40px;
}
h2#p-text {
  color: #1a1920;
  font-size: 30px;
}
h1#percent {
  color: #1a1920;
  font-size: 100px;
  margin-left: 25px;
}
h2#txtb4 {
  color: #1a1920;
  font-size: 30px;
}
h2#txtb5 {
  color: gray;
  font-size: 30px;
}
a:hover {
  filter: drop-shadow(0 0 10px white);
  transition: 0.5s;
}
.slide {
  margin-top: 50px;
  float: right;
  padding: 0 25px;
}
#leftarr {
    margin-right: 10px;
}
#rightarr {
    margin-left: 10px;
}
</style>
