<template>
  <div>
    <section id="home_page">
      <div class="container">
        <div class="row" id="first">
          <div class="col-6">
            <ul type="square">
              <li>
                Become a <br />
                pro-designer
              </li>
            </ul>
          </div>
          <div class="col-6">
            <div class="title">
              <h2 class="">Start guide for beginner designers</h2>
              <p>
                With UI,it’s easy to find the right music or podcast for
                every moment – on your phone, your computer,your tablet and
                more.
              </p>
            </div>
            <div class="buttongroup">
              <button>Let s start</button>
              <button>Read More</button>
            </div>
          </div>
        </div>
        <div class="row" id="number">
          <div class="col-4  mt-5">
            <span>+</span>
            <small>150</small>
            <h3>
              Happy <br />
              Students
            </h3>
          </div>
          <div class="col-4 mt-5">
            <span>+</span>
            <small>50</small>
            <h3>CERTIFIED <br />courses</h3>
          </div>
          <div class="col-4 mt-5">
            <span>+</span>
            <small>1000</small>
            <h3>AWARDS <br />RECEIVED</h3>
          </div>
        </div>
      </div>
    </section>
    <footer></footer>
  </div>
</template>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Oswald:wght@200;300&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Krub:ital,wght@0,200;0,300;1,200&display=swap");
ul li {
  font-size: 19px;
  line-height: 26px;
  text-transform: uppercase;
  color: #ffffff;
  font-weight: 700;
  font-family: "Krub";
  margin-top: 460px;
  margin-left: 85px;
}
#home_page {
  background-image: url("../assets/img/bg.png");
  /* background-position: center; */
  background-repeat: no-repeat;
  background-size: cover;
background-position-y: 0px;
  padding-bottom: 25px;
  z-index: 1;
}
#home_page p {
  width: 660px;
  height: 210px;
  font-size: 14px;
  letter-spacing: 0px;
  line-height: 27px;
  color: #ffffff;
  font-weight: 600;
  font-family: "Krub";
  text-align: left;
  width: 280px;
}
#home_page h2 {
  font-size: 20px;
  letter-spacing: 1px;
  line-height: 29px;
  text-transform: uppercase;
  color: #ffffff;
  font-weight: 600;
  font-family: "Krub";
  width: 280px;
}
#home_page button {
  width: 125px;
  height: 45px;
  background-color: #a460f9;
  font-size: 14px;
  letter-spacing: 1px;
  text-transform: uppercase;
  color: #ffffff;
  font-weight: 700;
  font-family: "Oswald";
  border: none;
  margin-left: 10px;
}
.buttongroup {
  margin-left: 280px;
  display: flex;
  margin-top: -100px;
}
.title {
  margin-top: 340px;
  margin-left: 290px;
}
#home_page span {
  font-size: 51px;
  color: #a460f9;
  margin-top: 60px;
}
#home_page small {
  font-size: 51px;
  color: #ffff;
  font-weight: bold;
  font-family: "Oswald";
  margin-top: 60px;
}
#home_page h3 {
  font-size: 22px;
  letter-spacing: 2px;
  color: #ffffff;
  font-weight: 400;
  font-family: "Krub";
  margin-top: 75px;
  margin-left: 10px;
}
#number {
  margin-top: 100px;
  margin-left: 80px;
}
#number .col-4{
  display: flex;
}
/* responsive css start */
@media screen and (min-width: 320px) and (max-width:480px){

#number{
  margin-top: 0px;
  margin-left: 0px;
}
#number .col-4{
  display: flex;
  /* flex-direction: column; */
}

#home_page span{
  font-size: 25px;
  margin-top: 70px;
}
.buttongroup{
      margin-left: 167px;
      display: none;
    margin-top: 0px; 
   
}
ul li{
  margin-left: 0px;
  margin-top: 0px;
  font-size: 14px;
}
.title{
  margin-left: 27px;
    margin-top: 50px;
}
#first{
  display: flex;
  flex-direction: column;
}
#home_page p{
  height: 90px;
  font-size: 10px;
  width: 150px;
  line-height: normal;
}
#home_page h2{
  font-size: 12px;
  width: 160px;
}
#home_page h3{
  font-size: 7px;
  margin-left: 5px;
}
#home_page small{
  font-size: 12px;
  margin-top: 75px;
}
#home_page button{
  font-size: 10px;
  width: 70px;
  height: 30px;
}
#home_page span{
  font-size: 17px;
}

}

</style>