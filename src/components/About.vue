<template>
  <div class="container-fluid">
    <div>
      <div class="about_">
        <div class="row">
          <div class="col-6" id="about_1">
            <div class="about-title">
              <h1>About <span>Us.</span></h1>
              <p>
                UI transformed music listening forever when it launched in 2008.
                Discover,manage and share over 80 million tracks,including 4.7
                million podcasts,for free, or upgrade to UI Premium to access
                exclusive features for music including improved sound quality
                and an on-demand, offline,and ad-free music listening
                experience.<br />Our missionis to unlock the potential of human
                creativity—by giving a million creative artists the opportunity
                to live off their art and billions of fans the opportunity to
                enjoy and be inspired by it.
              </p>
            </div>
            <div class="about_ul">
              <div class="about_div d-flex">
                <ul type="square">
                  <li><a href="#">UI GmbH</a></li>
                  <li><a href="#">Square de Meeus 37</a></li>
                </ul>
                <ul type="square" class="offset-3">
                  <li><a href="#">Regeringsgatan 19</a></li>
                  <li><a href="#">SE-111 53 Stockholm</a></li>
                </ul>
              </div>
            </div>
          </div>
          <div class="col-6"></div>
        </div>
      </div>
    </div>
    <div class="team-boxed">
      <div class="container">
        <div class="intro">
          <h1 id="about_h1">Top Beneficial Owners</h1>
          <p class="text-center" style="font-style: oblique">
            Nunc luctus in metus eget fringilla. Aliquam sed justo ligula.
            Vestibulum nibh erat, pellentesque ut laoreet vitae.
          </p>
        </div>
        <div class="row people">
          <div class="col-md-6 col-lg-4 item">
            <div class="box">
              <img class="rounded-circle" src="../assets/img/daniel.png" />
              <h3 class="name">Daniel Ek</h3>
              <p class="title">Entrepreneur</p>
              <p
                class="description"
                style="font-style: oblique 10deg; color: #181818"
              >
                Our missionis to unlock the potential of human creativity—by
                giving a million creative artists the opportunity to live off
                their art and billions of fans the opportunity to enjoy and be
                inspired by it.
              </p>
              <div class="social">
                <a href="https://www.facebook.com/eldsjal"
                  ><i class="fa-brands fa-facebook"></i></a
                ><a href="https://twitter.com/eldsjal"
                  ><i class="fa-brands fa-twitter"></i></a
                ><a href="https://www.instagram.com/eldsjal/"
                  ><i class="fa-brands fa-instagram"></i
                ></a>
              </div>
            </div>
          </div>
          <div class="col-md-6 col-lg-4 item">
            <div class="box">
              <img
                class="rounded-circle"
                src="../assets/img/martin-lorentzon.png"
              />
              <h3 class="name">Martin Lorentzon</h3>
              <p class="title">Producer</p>
              <p
                class="description"
                style="font-style: oblique 10deg; color: #181818"
              >
                Our missionis to unlock the potential of human creativity—by
                giving a million creative artists the opportunity to live off
                their art and billions of fans the opportunity to enjoy and be
                inspired by it.
              </p>
              <div class="social">
                <a href="https://www.facebook.com/martin.lorentzon"
                  ><i class="fa-brands fa-facebook"></i></a
                ><a href="https://twitter.com/martinlorentzon"
                  ><i class="fa-brands fa-twitter"></i></a
                ><a href="https://www.instagram.com/martin_lorentzon/"
                  ><i class="fa-brands fa-instagram"></i
                ></a>
              </div>
            </div>
          </div>
          <div class="col-md-6 col-lg-4 item">
            <div class="box">
              <img class="rounded-circle" src="../assets/img/mmm.png" />
              <h3 class="name">Morgan Stanley</h3>
              <p class="title">Director</p>
              <p
                class="description"
                style="font-style: oblique 10deg; color: #181818"
              >
                Our missionis to unlock the potential of human creativity—by
                giving a million creative artists the opportunity to live off
                their art and billions of fans the opportunity to enjoy and be
                inspired by it.
              </p>
              <div class="social">
                <a href="https://www.facebook.com/martin.lorentzon"
                  ><i class="fa-brands fa-facebook"></i></a
                ><a href="https://twitter.com/martinlorentzon"
                  ><i class="fa-brands fa-twitter"></i></a
                ><a href="https://www.instagram.com/martin_lorentzon/"
                  ><i class="fa-brands fa-instagram"></i
                ></a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Krub:ital,wght@0,200;0,300;1,200&display=swap");

.about-title h1 {
  font-size: 61px;
  color: #ffffff;
  font-weight: 700;
  font-family: "Krub";
}
.about-title span {
  font-size: 61px;
  letter-spacing: 6px;
  color: #aa84f9;
  font-weight: 400;
  font-family: "Krub";
}
.about-title p {
  width: auto;
  font-size: 14px;
  color: #ffffff;
  font-weight: 600;
  font-family: "Krub";
  margin-top: 45px;
}
.about_ul li {
  font-size: 12px;
  line-height: 22px;
  text-transform: uppercase;
  color: #ffffff;
  font-weight: 700;
  font-family: "Krub";
  margin-top: 50px;
  /* margin-bottom: 100px; */
}
.about_div ul li {
  color: #aa84f9 !important;
}
.about_div a {
  color: #ffffff;
  text-decoration: none;
}
#about_1 {
  margin-top: 200px;
  margin-left: 30px;
}

.about_ {
  background-image: url("../assets/img/aboutbg.png");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  padding-bottom: 100px;
}
.container-fluid {
  background-color: #181818;
}
.team-boxed {
  color: #313437;
  background-color: #181818;
}

.team-boxed p {
  color: #7d8285;
}

.team-boxed h2 {
  font-weight: bold;
  margin-bottom: 40px;
  padding-top: 40px;
  color: inherit;
}

@media (max-width: 767px) {
  .team-boxed h2 {
    margin-bottom: 25px;
    padding-top: 25px;
    font-size: 24px;
  }
}

.team-boxed .intro {
  font-size: 16px;
  max-width: 500px;
  margin: 0 auto;
}

.team-boxed .intro p {
  margin-bottom: 0;
}

.team-boxed .people {
  padding: 50px 0;
}

.team-boxed .item {
  text-align: center;
}

.team-boxed .item .box {
  background-color: #aa84f9;
  text-align: center;
  padding: 30px;
  margin-bottom: 30px;
}

.team-boxed .item .name {
  font-weight: bold;
  margin-top: 28px;
  margin-bottom: 8px;
  color: inherit;
}

.team-boxed .item .title {
  text-transform: uppercase;
  font-weight: bold;
  color: #d0d0d0;
  letter-spacing: 2px;
  font-size: 13px;
}

.team-boxed .item .description {
  font-size: 15px;
  margin-top: 15px;
  margin-bottom: 20px;
}

.team-boxed .item img {
  max-width: 160px;
}

.team-boxed .social {
  font-size: 18px;
  color: #181818;
}

.team-boxed .social a {
  color: inherit;
  margin: 0 10px;
  display: inline-block;
  opacity: 0.7;
}

.team-boxed .social a:hover {
  opacity: 1;
}
#about_h1 {
  text-align: center;
  background-image: linear-gradient(to left, #553c9a, #b393d3);
  color: transparent;
  background-clip: text;
  -webkit-background-clip: text;
}
</style>