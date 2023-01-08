<template>
  <div>
    <div class="container-fluid" id="footer">
      <div class="row">
        <div class="col-3">
          <div class="about_title" id="about_foot">
            <h3>About</h3>
            <small></small>
          </div>
          <ul type="none" id="foot">
            <li><a href="">History</a></li>
            <li><a href=""> Our Team</a></li>
            <li><a href="">Mission Statement</a></li>
            <li><a href="">Terms & Condition</a></li>
            <li><a href="">Privacy Policy</a></li>
          </ul>
        </div>
        <div class="col-3">
          <div class="about_title">
            <h3>What we do</h3>
            <span></span>
          </div>
          <ul type="none" id="foot">
            <li><a href="">News and stories</a></li>
            <li><a href="">Publications</a></li>
            <li><a href="">Take action</a></li>
            <li><a href=""> Recomendations</a></li>
            <li><a href="">Help</a></li>
          </ul>
        </div>
        <div class="col-6">
        <div class="last_footer">
            <h4>Sign Up To Receive <p>Our Newsletter</p> </h4>
          <input type="text" class="form-control" >
          <div class="icons d-flex">
            <h5> Follow us!</h5>
           
              <a href="https://www.facebook.com/mehemmed.valehov.3"><i class="fa-brands fa-facebook"></i></a> 
            <a href="https://www.instagram.com/raphaelll.m/"><i class="fa-brands fa-instagram"></i></a>
            <a href="https://www.youtube.com/"><i class="fa-brands fa-youtube"></i></a>
            
          </div>
          
         
        </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Krub:ital,wght@0,200;0,300;1,200&display=swap");
#footer {
  background-color: #8c6eca;
  padding-bottom: 20px;
}
#footer span {
  width: 213px;
  height: 2px;
  background-color: #e6e6e6;
  margin-left: 35px;
  margin-bottom: 35px;
}
#footer h3 {
 display: flex;
 justify-content: center;
  padding-top: 15px;
  font-size: 33px;
  letter-spacing: 3px;
  color: black;
  font-weight: 700;
  font-family: "Krub";
}
#footer .about_title {
  display: flex;
  flex-direction: column;
}
#footer small {
  width: 115px;
  height: 2px;
  background-color: #e6e6e6;
  margin-left: 30px;
  margin-bottom: 35px;
}
#foot a {
  font-size: 25px;
  line-height: 44px;
  color: #ffffff;
  font-weight: 600;
  font-family: "Krub";
  text-decoration: none;
 
}
#footer h4{
 
  padding-top: 15px;
  font-size: 33px;
line-height: 49px;
color: #ffffff;
font-weight: 700;
font-family: "Krub";
text-align: right;
}
#footer p{
  color:#181818;
}
#footer input{
    width: 470px;
height: 63px;
margin-left: 120px;
border: 3px solid #f1f1f1;
background-color: #8c6eca;
}
.last_footer{
    display: flex;
    flex-direction: column;
    margin-right: 30px;
}
#footer h5{
    font-size: 25px;
line-height: 33px;
color: #ffffff;
font-weight: 500;
font-family: "Krub";

}
.icons{
   margin-top: 120px; 
   margin-left: 60px;
 
}

.icons i{
font-size: 50px;
border-radius: 32px;
color: #e6e6e6;
background-color: #8c6eca;
margin-left: 77px;

}
.icons i:hover{
  color: #181818;
}
#about_foot{
  margin-right: 105px;
}
#foot a:hover{
  color:#181818;
}
</style>