<template>
  <body>
    <div class="container">
      <div class="left_Side">
        <div class="profileText">
          <div class="imgBx">
            <img src="../assets/images/profile.jpg" />
          </div>
          <h2>林奕君<br /><span>Software Developer</span></h2>
        </div>
        <div class="contactInfo">
          <div class="title">Contact Info</div>
          <ul>
            <li>
              <span class="icon"><i class="fa-regular fa-envelope"></i></span>
              <span class="text">stu112114@gmail.com</span>
            </li>
            <li>
              <span class="icon"><i class="fa-solid fa-globe"></i></span>
              <span class="text">movemessage.com</span>
            </li>
            <li>
              <span class="icon"><i class="fa-brands fa-linkedin-in"></i></span>
              <span class="text">www.linkedin.com/me</span>
            </li>
          </ul>
        </div>
      </div>
      <div class="right_Side"></div>
    </div>
  </body>
</template>
<script></script>
<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Poppins", sans-serif;
}
body {
  background: lightblue;
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
}
.container {
  position: relative;
  padding: 0px;
  width: 100%;
  max-width: 1000px;
  min-width: 100px;
  margin: 50px;
  background: #fff;
  display: grid;
  grid-template-columns: 1fr 2fr;
  box-shadow: 0 35px 55px rgba(0, 0, 0, 0.1);
}
.container .left_Side {
  position: relative;
  background: #003147;
  padding: 40px;
}
.container .right_Side {
  position: relative;
  background: #fff;
  padding: 40px;
}
.profileText {
  position: relative;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding-bottom: 20px;
  border-bottom: 1px solid rgba(255, 255, 255, 0.2);
}
.profileText .imgBx {
  position: relative;
  width: 200px;
  height: 200px;
  border-radius: 50%;
  overflow: hidden;
}
.profileText .imgBx img {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.profileText h2 {
  color: #fff;
  font-size: 1.5em;
  margin-top: 20px;
  text-transform: uppercase;
  text-align: center;
  font-weight: 600;
  line-height: 1.4em;
}
.profileText h2 span {
  font-size: 0.8em;
  font-weight: 300;
}
.contactInfo {
  padding-top: 40px;
}
.title {
  color: #fff;
  text-transform: uppercase;
  font-weight: 600;
  letter-spacing: 1px;
  margin-bottom: 20px;
}
.contactInfo ul {
  position: relative;
}
.contactInfo ul li {
  position: relative;
  list-style: none;
  margin: 10px 0;
  cursor: pointer;
}
.contactInfo ul li .icon {
  display: inline-block;
  width: 30px;
  font-size: 18px;
  color: #03a9f4;
}
.contactInfo ul li span {
  color: #fff;
  font-weight: 300;
}
</style>
