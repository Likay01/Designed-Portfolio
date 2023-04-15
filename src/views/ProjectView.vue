<template>
  <div class="heart">
        <div class="band">
          <div class="banding">
         <div class="container " id="cards">
    <div class="card sorted " style="width: 18rem;" >
        <img src="https://i.postimg.cc/mDXTRHDT/Screenshot-20230202-032508.png" class="images card-img-top" alt="...">
  <div class="card-bodyspace">
    <h5 class="card-title">Capital Control</h5>
    <div class="card-body">
                <button type="button" class="tie btn btn"><a :href="pro.Git" target="_blank" class="card-link">Github</a></button>
                <button type="button" class="tie btn btn"><a :href="pro.Net" target="_blank" class="card-link">Netify(Live)</a></button>
            </div>
          </div>
          </div>
            </div>

            <div class="container " id="cards">
    <div class="card sorted " style="width: 18rem;" >
        <img src="https://i.postimg.cc/ZqLcw8c8/Screenshot-20230119-022653.png" class="images card-img-top" alt="...">
  <div class="card-bodyspace">
    <h5 class="card-title">Vinylique</h5>
        <div class="card-body">
                <button type="button" class="tie btn btn"><a :href="pro.Git" target="_blank" class="card-link">Github</a></button>
                <button type="button" class="tie btn btn"><a :href="pro.Net" target="_blank" class="card-link">Netify(Live)</a></button>
            </div>
        </div>
          </div>
            </div>


            <div class="container " id="cards">
    <div class="card sorted " style="width: 18rem;" >
        <img src="https://i.postimg.cc/259pSc96/Screenshot-20230119-033824.png" class="images card-img-top" alt="...">
  <div class="card-bodyspace">
    <h5 class="card-title">Calculator</h5>
        <div class="card-body">
                <button type="button" class="tie btn btn"><a :href="pro.Git" target="_blank" class="card-link">Github</a></button>
                <button type="button" class="tie btn btn"><a :href="pro.Net" target="_blank" class="card-link">Netify(Live)</a></button>
            </div>
        </div>
          </div>
            </div>


            <div class="container " id="cards">
    <div class="card sorted " style="width: 18rem;" >
        <img src="https://i.postimg.cc/hGQtzb08/screen.png" class="images card-img-top" alt="...">
  <div class="card-bodyspace">
    <h5 class="card-title">Grid </h5>
        <div class="card-body">
                <button type="button" class="tie btn btn"><a :href="pro.Git" target="_blank" class="card-link">Github</a></button>
                <button type="button" class="tie btn btn"><a :href="pro.Net" target="_blank" class="card-link">Netify(Live)</a></button>
            </div>
        </div>
          </div>
            </div>


            <div class="container " id="cards">
    <div class="card sorted " style="width: 18rem;" >
        <img src="https://i.postimg.cc/mkdHQ5mM/1679909303854.jpg" class="images card-img-top" alt="...">
  <div class="card-bodyspace">
    <h5 class="card-title">Timothy Jennike </h5>
        <div class="card-body">
                <button type="button" class="tie btn btn"><a :href="pro.Git" target="_blank" class="card-link">Github</a></button>
                <button type="button" class="tie btn btn"><a :href="pro.Net" target="_blank" class="card-link">Netify(Live)</a></button>
            </div>
        </div>
          </div>
            </div>


            <div class="container " id="cards">
    <div class="card sorted " style="width: 18rem;" >
        <img src="https://i.postimg.cc/T1nwCH2h/C11-Brandon-Swinton-1.jpg" class="images card-img-top" alt="...">
  <div class="card-bodyspace">
    <h5 class="card-title">Brandon Swinton</h5>
        <div class="card-body">
                <button type="button" class="tie btn btn"><a :href="pro.Git" target="_blank" class="card-link">Github</a></button>
                <button type="button" class="tie btn btn"><a :href="pro.Net" target="_blank" class="card-link">Netify(Live)</a></button>
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

 
    } 
</script>
<style scoped>
      .heart{
    height:100vh;
    background-color: #100f0f;
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 400;
    display:flex;
position: relative;
place-items: center;
overflow: hidden;
  }
  .card{
    width: 0;
    height: 25rem;
    background-color: #C0BB05;
    transition: transform 2s;
    object-fit: contain;
  }
  #cards{
     display: inline-flex; 
     flex-wrap: wrap;
     gap: 3rem;
     position: relative;
 height:30rem;
 margin: 0;
 width: 30rem;
 display: grid;
 place-items: center;
padding: 10px;
perspective: 700px;
    }
    img{
height: 200px;
width: 100%;
}
.card:hover{
  transform: translateZ(3rem);
}
.banding{
  display: flex;
  width: calc(250px * 18);
  animation: scroll 40s linear infinite;
}
.band{
    background-color:#FFF804; 
    height: 90vh;
}
.banding:hover{
  animation-play-state: paused;
}
@keyframes scroll {
  0%{
    transform: translateX(0);
  }
  100%{
    transform: translateX(calc(-250px * 9));
  }
}
</style>