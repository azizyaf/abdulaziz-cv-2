<template>
  <div>
    <div class="container-fluid px-0">
      <div class="row">
        <div class="col-md-6 img" data-aos="fade-right">
          <img src="..\assets\me.jpg" class="img-thumbnail border border-warning rounded-pill">
        </div>
        <div class="col-md-6 about-me" data-aos="fade-left">
          <div class="container">
            <h1>About Me</h1>
            <p>A Full-Stack Web Developer. Curious to learn new things and gain new skills especially about technology, I believe I can make an immediate impact in any task i'm assigned to do with my unique blend of skills and passion. Intrested on about Data analytics, Data science, Big data and Machine Learning. Been engaged in many software applications mainly web applications.</p>
            <div>
              <div class="fas fa-pray"></div>
              <div class="fas fa-utensils"></div>
              <div class="fas fa-dumbbell"></div>
              <div class="fas fa-tasks"></div>
              <div class="fas fa-bed"></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.row{
  min-height: 100vh;
}
img{
  width: 400px;
	height: 400px;
  margin-top: 80px;
}
.img{
  background-color:#D2D2D2;
  display: flex;
  justify-content: center;
  align-content: center;
}
.about-me{
  background-color:black;
  justify-content: center;
}
.container{
  margin-top: 150px;
}
h1{
  font-family: 'Modak', cursive;
  color: #EFDD00;
}
p{
  font-family: 'Muli', sans-serif;
  color: aliceblue;
}
.fab, .fas{
  font-size: 50px;
  margin-right: 50px;
  margin-top: 20px;
  color: #EFDD00;
}

@media (max-width: 1097px) {
  img{
    width: 200px;
    height: 200px;
    margin-top: 80px;
  }
  .container{
    margin-top: 70px;
  }
  h1{
  font-family: 'Modak', cursive;
  color: #EFDD00;
  font-size: 30px;
  }
  p{
    font-family: 'Muli', sans-serif;
    color: aliceblue;
    font-size: 18px;
  }
  .fab, .fas{
    font-size: 30px;
    margin-right: 50px;
    margin-top: 20px;
    color: #EFDD00;
  }
  
}

@media (max-width: 897px) {
  img{
    width: 200px;
    height: 200px;
    margin-top: 90px;
  }
  .container{
    margin-top: 60px;
  }
  h1{
  font-family: 'Modak', cursive;
  color: #EFDD00;
  font-size: 30px;
  }
  p{
    font-family: 'Muli', sans-serif;
    color: aliceblue;
    font-size: 15px;
  }
  .fab, .fas{
    font-size: 20px;
    margin-right: 30px;
    margin-top: 20px;
    color: #EFDD00;
  }
  
}

@media (max-width: 767px) {
  img{
    width: 200px;
    height: 200px;
    margin-top: 40px;
    margin-bottom: 40px;
  }
  .container{
    margin-top: 30px;
    margin-bottom: 30px;
    text-align: center;
  }
  h1{
  font-family: 'Modak', cursive;
  color: #EFDD00;
  font-size: 30px;
  }
  p{
    font-family: 'Muli', sans-serif;
    color: aliceblue;
    font-size: 15px;
  }
  .fab, .fas{
    font-size: 20px;
    margin-right: 30px;
    margin-top: 20px;
    color: #EFDD00;
  }
  
}
</style>