<script setup>
// import {logoInst} from '../components/icons/logoInst.png'
</script>

<template>
 <div class="flex flex-col items-center gap-10">
  <div class="">
    <div class="justify-center items-center flex shadow-2xl shadow-blue-950  bg-gradient-to-r from-purple-500 to-pink-500 p-[2px] bg-black mt-24 m-auto w-[150px] h-[150px] select-none rounded-full">
     
    <img class="w-[140px] bg-center bg-no-repeat bg-scroll h-[140px] rounded-full" src="../components//icons/persone.jpg" alt="">
    </div>
    <div class="flex flex-col text-white rounded-lg p-2 mt-5 w-[300px] h-auto backdrop-blur-sm border border-gray-600">
      <!-- <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit nulla dolores fugiat beatae corporis pariatur obcaecati quam tempora. Facere possimus deleniti soluta excepturi magni fugiat nobis aliquid, nesciunt ullam quibusdam.</p> -->
      <svg class="absolute top-2 right-2 fill-white" xmlns="http://www.w3.org/2000/svg" id="Layer_1" data-name="Layer 1" viewBox="0 0 24 24" width="20" height="20"><path d="M12,24A12,12,0,1,1,24,12,12.013,12.013,0,0,1,12,24ZM12,2A10,10,0,1,0,22,12,10.011,10.011,0,0,0,12,2Zm5.666,13.746a1,1,0,0,0-1.33-1.494A7.508,7.508,0,0,1,12,16a7.509,7.509,0,0,1-4.334-1.746,1,1,0,0,0-1.332,1.492A9.454,9.454,0,0,0,12,18,9.454,9.454,0,0,0,17.666,15.746ZM6,10c0,1,.895,1,2,1s2,0,2-1a2,2,0,0,0-4,0Zm8,0c0,1,.895,1,2,1s2,0,2-1a2,2,0,0,0-4,0Z"/></svg>
      <p class="text-slate-400">Founder: <span class="text-white font-medium">Jasur</span></p>
      <p class="text-slate-400">UserName: <span class="text-white">WebHero</span></p>
      <p class="text-slate-400">Profession: <span class="text-white">FullStack Developer</span></p></div>
  </div>
  <div class="max-w-[500px] w-full h-auto  flex flex-col items-center gap-4 ">
    <a href="https://t.me/jasurdevich">
      <button type="button" class="btn">
        <strong>Telegram</strong>
        <div id="container-stars">
          <div id="stars"></div>
        </div>
      
        <div id="glow">
          <div class="circle"></div>
          <div class="circle"></div>
        </div>
      </button>
    </a>
    <a href="/#/">
      <button type="button" class="btn">
        <strong>WebSite</strong>
        <div id="container-stars">
          <div id="stars"></div>
        </div>
      
        <div id="glow">
          <div class="circle"></div>
          <div class="circle"></div>
        </div>
      </button>
    </a>
   <a href="https://www.instagram.com/webhero.dev/profilecard/?igsh=MWV6dDlmc2RpeHN3bw==">
    <button type="button" class="btn">
      <strong>Instagram</strong>
      <div id="container-stars">
        <div id="stars"></div>
      </div>
    
      <div id="glow">
        <div class="circle"></div>
        <div class="circle"></div>
      </div>
    </button>
   </a>
    <a href="https://www.tiktok.com/@webhero.dev?_t=8qt9pvQD8lu&_r=1">
        <button type="button"  class="btn">
        <strong>TikTok</strong>
        <div id="container-stars">
          <div id="stars"></div>
        </div>
      
        <div id="glow">
          <div class="circle"></div>
          <div class="circle"></div>
        </div>
      </button>
      </a>
  </div>
 
  <div class="flex flex-col rounded-lg p-2 mt-5 w-auto mb-28 h-auto backdrop-blur-sm border border-gray-600 text-slate-400 text-nowrap">
    <p>По любым предложением писать в личку! </p>
  </div>
 </div>
</template>
<style>
/* From Uiverse.io by adamgiebl */ 

/* From Uiverse.io by StealthWorm */ 
.btn {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 300px;
  overflow: hidden;
  height: 50px;
  background-size: 300% 300%;
  cursor: pointer;
  backdrop-filter: blur(1rem);
  border-radius: 5rem;
  transition: 0.5s;
  animation: gradient_301 5s ease infinite;
  border: double 4px transparent;
  background-image: linear-gradient(#212121, #212121),
    linear-gradient(
      137.48deg,
      #ffdb3b 10%,
      #fe53bb 45%,
      #8f51ea 67%,
      #0044ff 87%
    );
  background-origin: border-box;
  background-clip: content-box, border-box;
}

#container-stars {
  position: absolute;
  z-index: -1;
  width: 100%;
  height: 100%;
  overflow: hidden;
  transition: 0.5s;
  backdrop-filter: blur(1rem);
  border-radius: 5rem;
}

strong {
  z-index: 2;
  font-family: "Avalors Personal Use";
  font-size: 12px;
  letter-spacing: 5px;
  color: #ffffff;
  text-shadow: 0 0 4px white;
}

#glow {
  position: absolute;
  display: flex;
  width: 12rem;
}

.circle {
  width: 100%;
  height: 30px;
  filter: blur(2rem);
  animation: pulse_3011 4s infinite;
  z-index: -1;
}

.circle:nth-of-type(1) {
  background: rgba(254, 83, 186, 0.636);
}

.circle:nth-of-type(2) {
  background: rgba(142, 81, 234, 0.704);
}

.btn:hover #container-stars {
  z-index: 1;
  background-color: #212121;
}

.btn:hover {
  transform: scale(1.1);
}

.btn:active {
  border: double 4px #fe53bb;
  background-origin: border-box;
  background-clip: content-box, border-box;
  animation: none;
}

.btn:active .circle {
  background: #fe53bb;
}

#stars {
  position: relative;
  background: transparent;
  width: 200rem;
  height: 200rem;
}

#stars::after {
  content: "";
  position: absolute;
  top: -10rem;
  left: -100rem;
  width: 100%;
  height: 100%;
  animation: animStarRotate 90s linear infinite;
}

#stars::after {
  background-image: radial-gradient(#ffffff 1px, transparent 1%);
  background-size: 50px 50px;
}

#stars::before {
  content: "";
  position: absolute;
  top: 0;
  left: -50%;
  width: 170%;
  height: 500%;
  animation: animStar 60s linear infinite;
}

#stars::before {
  background-image: radial-gradient(#ffffff 1px, transparent 1%);
  background-size: 50px 50px;
  opacity: 0.5;
}

@keyframes animStar {
  from {
    transform: translateY(0);
  }

  to {
    transform: translateY(-135rem);
  }
}

@keyframes animStarRotate {
  from {
    transform: rotate(360deg);
  }

  to {
    transform: rotate(0);
  }
}

@keyframes gradient_301 {
  0% {
    background-position: 0% 50%;
  }

  50% {
    background-position: 100% 50%;
  }

  100% {
    background-position: 0% 50%;
  }
}

@keyframes pulse_3011 {
  0% {
    transform: scale(0.75);
    box-shadow: 0 0 0 0 rgba(0, 0, 0, 0.7);
  }

  70% {
    transform: scale(1);
    box-shadow: 0 0 0 10px rgba(0, 0, 0, 0);
  }

  100% {
    transform: scale(0.75);
    box-shadow: 0 0 0 0 rgba(0, 0, 0, 0);
  }
}

</style>
