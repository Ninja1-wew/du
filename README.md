<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Dhaka University Admission</title>

  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.css" rel="stylesheet">

  <style>
    body {
      height: 100vh;
      background: radial-gradient(circle at top left, #002b36, #0f2027);
      display: flex;
      justify-content: center;
      align-items: center;
      color: #fff;
      font-family: 'Poppins', sans-serif;
      overflow: hidden;
      position: relative;
    }

    .banner {
      display: inline-block;
      background: #ffeb3b;
      color: #000;
      font-weight: 600;
      letter-spacing: 1px;
      border-radius: 50px;
      padding: 0.75rem 2rem;
      margin-bottom: 2rem;
      box-shadow: 0 4px 20px rgba(255, 235, 59, 0.5);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .banner:hover { transform: scale(1.05); box-shadow: 0 6px 30px rgba(255,235,59,0.8); }

    .countdown { display:flex; justify-content:center; gap:1rem; text-align:center; }
    .time-box {
      background: rgba(255,255,255,0.15);
      backdrop-filter: blur(10px);
      border-radius: 16px;
      padding: 1rem 1.5rem;
      box-shadow: 0 0 20px rgba(255,235,59,0.4);
      transition: transform .3s ease, box-shadow .3s ease;
    }
    .time-box:hover { transform: scale(1.05); box-shadow: 0 0 35px rgba(255,235,59,0.8); }

    footer { position:absolute; bottom:15px; font-size:.85rem; color:rgba(255,255,255,0.7); }
  </style>
</head>
<body>
  <div class="container text-center" data-aos="fade-up">
    <div class="banner">WELCOME TO DHAKA UNIVERSITY ADMISSION</div>
    <h1 class="mb-3">⏳ War Starts In</h1>
    <p class="mb-4 text-light">Stay focused — every second counts!</p>

    <div class="countdown">
      <div class="time-box">
        <div id="days" class="fs-2 fw-bold">00</div><div>Days</div>
      </div>
      <div class="time-box">
        <div id="hours" class="fs-2 fw-bold">00</div><div>Hours</div>
      </div>
      <div class="time-box">
        <div id="minutes" class="fs-2 fw-bold">00</div><div>Minutes</div>
      </div>
      <div class="time-box">
        <div id="seconds" class="fs-2 fw-bold">00</div><div>Seconds</div>
      </div>
    </div>
  </div>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.js"></script>

  <!-- Minified + deterrent script (copy-paste as-is) -->
  <script>
  AOS.init();(function(){try{const s=localStorage.getItem("countdownTarget");let t=s?new Date(s):null;if(!t){t=new Date();t.setDate(t.getDate()+50);localStorage.setItem("countdownTarget",t.toString())}function u(){const e=Date.now(),n=t-e,o=Math.floor(n/864e5),r=Math.floor(n%864e5/36e5),a=Math.floor(n%36e5/6e4),i=Math.floor(n%6e4/1e3);document.getElementById("days").textContent=String(Math.max(0,o)).padStart(2,"0"),document.getElementById("hours").textContent=String(Math.max(0,r)).padStart(2,"0"),document.getElementById("minutes").textContent=String(Math.max(0,a)).padStart(2,"0"),document.getElementById("seconds").textContent=String(Math.max(0,i)).padStart(2,"0"),n<0&&(clearInterval(g),document.querySelector(".container").innerHTML='<h1 class="text-warning">✅ Application Started!</h1>')}const g=setInterval(u,1e3);u(),document.addEventListener("contextmenu",function(e){e.preventDefault();return!1}),document.addEventListener("keydown",function(e){if(123===e.keyCode){e.preventDefault();return!1}if(e.ctrlKey&&e.shiftKey&&(e.key==="I"||e.key==="i")){e.preventDefault();return!1}if(e.ctrlKey&&e.shiftKey&&(e.key==="J"||e.key==="j")){e.preventDefault();return!1}if(e.ctrlKey&&(e.key==="U"||e.key==="u")){e.preventDefault();return!1}if(e.ctrlKey&&(e.key==="S"||e.key==="s")){e.preventDefault();return!1}if(e.ctrlKey&&e.shiftKey&&(e.key==="C"||e.key==="c")){e.preventDefault();return!1}}),(function(){let e=!1,n=160;function t(){const t=window.outerWidth-window.innerWidth>n,o=window.outerHeight-window.innerHeight>n;e=t||o,e&&(document.body.style.display="none")}window.addEventListener("resize",t),setInterval(t,1e3)})();try{const e=function(){};Object.defineProperty(window,"console",{configurable:!1,enumerable:!1,writable:!1,value:{log:e,info:e,warn:e,error:e,debug:e,table:e}})}catch(e){} }catch(e){/* ignore errors */}})();
  </script>
</body>
</html>
