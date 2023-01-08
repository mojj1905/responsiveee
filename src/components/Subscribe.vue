<template>
  <div class="container-fluid">
    <section id="sub">
      <div class="row">
        <div class="col-6"></div>
        <div class="col-6" id="bg">
          <h1>SUBSCRIBE</h1>
          <h2>to our newsletter</h2>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Nobis
            similique aliquid eum libero! Consequuntur voluptates eveniet esse
            doloremque at officiis!
          </p>
          <form id="form">
            <input type="text" class="text form-control" placeholder="NAME" />
            <input type="text" class="text form-control" placeholder="MAIL" />
            <input
              type="text"
              id="yazi"
              placeholder="MESSAGE"
              class="form-control"
            />
            <div class="buttong">
              <button>Send Message</button>
            </div>
          </form>
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Krub:ital,wght@0,200;0,300;1,200&display=swap");
#bg {
  margin-top: 200px;
}
.container-fluid {
  background-image: url("../assets/img/Subscribe.png");
  background-size: auto;
  background-repeat: no-repeat;
  background-position-x: -450px;
  background-color: #181818;
  background-position-y: 45px;
}
#form .text {
  margin-bottom: 50px;
  width: 510px;
  height: 68px;
  background-color: inherit;
  border: 3px solid #9172d1;
  padding-left: 15px;
  font-size: 17px;
  letter-spacing: 3px;
  color: #6a6a6a;
  font-weight: 700;
  font-family: "Krub";
}
#form button {
  font-size: 14px;
  letter-spacing: 1px;
  text-transform: uppercase;
  color: #f1f1f1;
  font-weight: 700;
  font-family: "Oswald";
  width: 169px;
  height: 63px;
  background-color: #8c6eca;
  border: none;
}
.buttong {
  margin-left: 175px;
  padding-bottom: 70px;
}
#yazi {
  margin-bottom: 80px;
  width: 510px;
  height: 178px;
  background-color: inherit;
  border: 3px solid #9172d1;
  padding-bottom: 120px;
  padding-left: 15px;
  font-size: 17px;
  letter-spacing: 3px;
  color: #6a6a6a;
  font-weight: 700;
  font-family: "Krub";
}
#sub h1 {
  font-size: 47px;
  text-transform: uppercase;
  color: #ffffff;
  font-weight: 700;
  font-family: "Krub";
  display: flex;
  justify-content: center;
  width: 510px;
}
#sub h2 {
  font-size: 46px;
  letter-spacing: 5px;
  color: #8a6dc7;
  font-weight: 400;
  font-family: "Krub";
  display: flex;
  justify-content: center;
  width: 510px;
}
#sub p {
  width: 510px;
  font-size: 16px;
  color: #ffffff;
  font-weight: 600;
  font-family: "Krub";
  text-align: center;
}
</style>
