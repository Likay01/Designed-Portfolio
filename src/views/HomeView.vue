<template>
    <div class="heart">
       <div class="reg-1">
        <div class="head col">
        <h6 class="intro">HI THERE, I'M </h6>
        <h3 class="name">LINDOKUHLE MGOQI</h3>
        <div class="board">
            <h6>Intern Full-Stack Developer</h6>
        </div>
        </div>
        <div class="photo col">
        <img class="imgs" src="https://i.postimg.cc/wMk1R9Q2/DSC-3517.jpg" width="50">
        </div>
       </div>
       <router-link to="/resume">
            <div class="resume">
        <img class="stat" src="https://i.postimg.cc/GmRjfj2T/My-project-1.png" width="50">
        <h3 class="res">RESUME</h3>
      </div> 
       </router-link>
       <router-link to="/projects">
         <div class="projects">
        <img class="web" src="https://i.postimg.cc/nLjgFk4V/My-project-1-2.png" width="50">
        <h3 class="pro">PROJECTS</h3>
      </div> 
       </router-link>
       <router-link to="/testimonials">
            <div class="testimonial">
        <img class="pg" src="https://i.postimg.cc/nhZhQXRt/My-project-1-1.png" width="50">
        <h3 class="test">TESTIMONIALS</h3>
      </div> 
       </router-link>

    </div>
  
</template>
<script>
export default {
    
}
</script>
<style scoped>
.imgs{
    box-sizing: border-box;
position: absolute;
width: 250px;
height: 250px;
left: 72rem;
top: 20px;
border: 2px solid rgba(34, 113, 115, 0.69);
border-radius: 130px;
}
  .heart{
    height:100vh;
    background-color: #100f0f;
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 400;
  }
  .head{
    padding: 0;
  }
  .intro{
position: absolute;
font-size: 25px;
margin-top: -25px;
margin-left: 55px;
color: #F1F1F1;
  }  
  .name{  
text-align: start;
font-size: 70px;
margin-top: 120px;
margin-left: 50px;
color: #0C2B2C;
  }
  .board{
box-sizing: border-box;
position: absolute;
width: 362px;
height: 35px;
left: 50px;
top: 230px;
border: 1px solid #0C2B2C;
border-radius: 10px;
  }
  h6{
    margin-top: 5px;
    color: #0C2B2C;
    font-weight: bold;
  }
  .reg-1{
    box-sizing: border-box;
position: absolute;
width: 97vw;
height: 300px;
margin-left: 10px; 
background: #268D8F;
border: 5px solid #0C2B2C;
border-radius: 15px;
  }
  .resume{
position: absolute;
width: 32vw;
height: 300px;
margin-left: 10px; 
background: #EF5B0E;
border: 5px solid #943707;
border-radius: 15px;
top:385px;
  }
  .res{
    position: absolute;
width: 390px;
height: 87px;
top: 210px;
text-align: start;
font-family: 'Montserrat';
font-style: normal;
font-weight: 700;
font-size: 65px;
color: #943707;
  }
  .projects{
position: absolute;
width: 30vw;
height: 300px;
margin-left: 10px; 
background: #FFF804;
border: 5px solid #C0BB05;
border-radius: 15px;
top:385px;
left: 32rem;
  }
  .pro{
    position: absolute;
width: 390px;
height: 87px;
top: 210px;
text-align: start;
font-family: 'Montserrat';
font-style: normal;
font-weight: 700;
font-size: 65px;
color: #C0BB05;
}
  .testimonial{
position: absolute;
width: 32vw;
height: 300px;
margin-left: 10px; 
background: #3CCF4E;
border: 5px solid #24722D;
border-radius: 15px;
top:385px;
left:62rem;
  }
  .test{
    position: absolute;
width: 390px;
height: 87px;
left: 5px;
top: 210px;
text-align: start;
font-family: 'Montserrat';
font-style: normal;
font-weight: 700;
font-size: 55px;
color: #24722D;
  }
.stat{
position: absolute;
width: 320px;
height: 230px;
left: 170px;
top: 15px;
}
.web{
position: absolute;
width: 320px;
height: 250px;
left: 170px;
top: -20px;
}
.pg{
position: absolute;
width: 280px;
height: 260px;
left: 220px;
top: -15px;
}
</style>