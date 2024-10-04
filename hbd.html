<!DOCTYPE html>
<html lang="id">
<meta charset='UTF-8'/><meta content='width=device-width, initial-scale=1, user-scalable=1, minimum-scale=1, maximum-scale=5' name='viewport'/><meta content='IE=edge' http-equiv='X-UA-Compatible'/>
  
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Shippori+Antique:wght@400;700&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Dancing+Script&display=swap" rel="stylesheet">

  <script src="https://cdn.jsdelivr.net/npm/sweetalert2@11.0.19/dist/sweetalert2.all.min.js"></script><link href="https://feeldreams.github.io/heihbd/style.css" rel="stylesheet" type="text/css" />
  <script src="https://unpkg.com/typeit@8.7.0/dist/index.umd.js"></script>
  <script src="https://kit.fontawesome.com/4f3ce16e3e.js" crossorigin="anonymous"></script>
     <style>* {
   margin: 0;
   padding: 0;
   }
   
   body {
   background-color: black;
   }
   
   h1 {
   margin-top: 5%;
   font-family: 'Segoe UI';
   font-size: 60px;
   text-align: center;
   color: white;
   }
   </style>
   <h1>HAPPY BIRTHDAY SAYANG</h2>
   <script>var rnd = Math.random, flr = Math.floor;
   let canvas = document.createElement('canvas');
   
   document.getElementsByTagName('body')[0].appendChild(canvas);
   canvas.style.position = 'absolute';
   canvas.style.width = '100%';
   canvas.style.height = '100%';
   
   canvas.width = canvas.clientWidth;
   canvas.height = canvas.clientHeight;
   
   let ctx = canvas.getContext('2d');
   
   function rndNum(num) {
   return rnd() * num + 1;
   }
   
   function vector(x, y) {
   this.x = x;
   this.y = y;
   
   this.add = function(vec2) {
   this.x = this.x + vec2.x;
   this.y = this.y + vec2.y;
   }
   }
   
   function particle(pos, vel) {
   this.pos = new vector(pos.x, pos.y);
   this.vel = vel;
   this.finish = false;
   this.start = 0;
   
   this.update = function(time) {
   let timeSpan = time - this.start;
   
   if (timeSpan > 500) {
   this.finish = true;
   }
   
   if (!this.finish) {
   this.pos.add(this.vel);
   this.vel.y = this.vel.y + gravity;
   }
   };
   
   this.draw = function() {
   if (!this.finish) {
   drawDot(this.pos.x, this.pos.y, 1);
   }
   }
   
   }
   
   function firework(x, y) {
   this.pos = new vector(x, y);
   this.vel = new vector(0, -rndNum(10) - 3);
   this.color = 'hsl(' + rndNum(360) + ', 100%, 50%)'
   this.size = 4;
   this.finish = false;
   this.start = 0;
   let exParticles = [], exPLen = 100;
   
   let rootShow = true;
   
   this.update = function(time) {
   if (this.finish) {
   return;
   }
   
   rootShow = this.vel.y < 0;
   
   if (rootShow) {
   this.pos.add(this.vel);
   this.vel.y = this.vel.y + gravity;
   } else {
   if (exParticles.length === 0) {
   flash = true;
   for (let i = 0; i < exPLen; i++) {
   exParticles.push(new particle(this.pos, new vector(-rndNum(10) + 5, -rndNum(10) + 5)));
   exParticles[exParticles.length - 1].start = time;
   }
   }
   let countFinish = 0;
   for (let i = 0; i < exPLen; i++) {
   let p = exParticles[i];
   p.update(time);
   if (p.finish) {
   countFinish++;
   }
   }
   
   if (countFinish === exPLen) {
   this.finish = true;
   }
   
   }
   }
   
   this.draw = function() {
   if (this.finish) {
   return;
   }
   
   ctx.fillStyle = this.color;
   if (rootShow) {
   drawDot(this.pos.x, this.pos.y, this.size);
   } else {
   for (let i = 0; i < exPLen; i++) {
   let p = exParticles[i];
   p.draw();
   }
   }
   }
   
   }
   
   function drawDot(x, y, size) {
   ctx.beginPath();
   
   ctx.arc(x, y, size, 0, Math.PI * 2);
   ctx.fill();
   
   ctx.closePath();
   }
   
   var fireworks = [],
   gravity = 0.2,
   snapTime = 0,
   flash = false;
   
   function init() {
   let numOfFireworks = 20;
   for (let i = 0; i < numOfFireworks; i++) {
   fireworks.push(new firework(rndNum(canvas.width), canvas.height));
   }
   }
   
   function update(time) {
   for (let i = 0, len = fireworks.length; i < len; i++) {
   let p = fireworks[i];
   p.update(time);
   }
   }
   
   function draw(time) {
   update(time);
   
   ctx.fillStyle = 'rgba(0,0,0,0.3)';
   if (flash) {
   flash = false;
   }
   ctx.fillRect(0, 0, canvas.width, canvas.height);
   
   ctx.fillStyle = 'white';
   ctx.font = "30px Segoe UI";
   let newTime = time - snapTime;
   snapTime = time;
   
   ctx.fillStyle = 'blue';
   for (let i = 0, len = fireworks.length; i < len; i++) {
   let p = fireworks[i];
   if (p.finish) {
   fireworks[i] = new firework(rndNum(canvas.width), canvas.height);
   p = fireworks[i];
   p.start = time;
   }
   p.draw();
   }
   
   window.requestAnimationFrame(draw);
   }
   
   window.addEventListener('resize', function() {
   canvas.width = canvas.clientWidth;
   canvas.height = canvas.clientHeight;
   });
   
   init();
   draw();
   </script>
<head>
<title>Happy Birthday</title>
<link rel="icon" type="image/x-icon" href="https://malasid.github.io/favicon.png">
<meta name="description" content="HTML Bucin Malas.id">
<!-- 
  Made with love by Rayys!
  
     Blog: https://PalingIT.com
     Instagram: @rayyarrr
     TikTok: @rayy4r
     Email: rayyar0703@gmail.com
     
  Thanks to all <3
-->
</head>
<body>

   <!-- Ganti Audio di sini https://feeldreams.github.io/djikhlas.mp3-->

   <audio src="https://music.apple.com/id/album/youre-still-the-one/1683922921?i=1683923128" id="linkmp3" class="sembunyi">
   </audio>
   
   <div id="bodyblur">
     <!-- Wallpaper --><img src="https://feeldreams.github.io/wp9.jpg" id="wallpaper"/><div id="beneranblur"></div>
   </div>
   
   <div id='Content'>

     <div id="kadoIn">
       <!-- Tombol Surat --><img src="https://feeldreams.github.io/kadoin.png"/>
     </div>
     <p id="ket">Klik Kadonya!</p>

     <div class="kumpulanstiker">
         <!-- Stiker untuk Konten -->
         <img src="https://feeldreams.github.io/bunga.gif" id="fotostiker"/>
         <img src="https://feeldreams.github.io/pusn.gif" id="fotostiker1"/>
         <img src="https://feeldreams.github.io/pandacoklat.gif" id="fotostiker2"/>
         <img src="https://feeldreams.github.io/cilukba.gif" id="fotostiker3"/>
         <img src="https://feeldreams.github.io/pandakuning.gif" id="fotostiker4"/>
         <img src="https://feeldreams.github.io/emawh.gif" id="fotostiker5"/>
         
         <img src="https://feeldreams.github.io/pandacoklat.gif" id="fotostiker6"/>
     </div>
     
     <p id="halo" class="halo"></p>
     
     <div><blockquote id='bq' data-text='yadi.ly'>
       <p id="kalimat">Aku Ada Sesuatu Ini Buat Kamu 🤣❤️</p>

       <p id="pesan1">Klik semua gambar dibawah 😆❤️</p>
       <div id="kolombaru">
         <li id="lv1">🤍</li>
         <li id="lv2">🤍</li>
         <li id="lv3">🤍</li>
         <li id="lv4">🤍</li>
       </div>

       <p id="pesan2">Waiting...............</p>
       <!-- Pesan -->
       <p id="pesan3">Akhirnya..... 🤣❤️ <br>
       Ada yang usianya semakin tua ini hahaha...</p>
       <!-- <p id="pesan">Ada yang usianya semakin tua ini hahaha...</p> -->
       <p id="pesan4">Happy Birthday ya sayang  </p>
       <p id="pesan5" class="gaya2">Semoga panjang umur lagi <br>
                                    Aku berdoa semoga TUHAN selalu melindungimu<br>
                                    Semoga kebahagiaan, kesehatan, dan kesuksesan yang ada dalam setiap langkahmu kedepannya <br>
                                    Semoga kamu bisa menggapai semua mimpimu, dan tentunya dengan semua harapanmu dapat terwujud <br>
                                    Tetap rendah hati, sayang sama orang tua dan keluarga semua, dan sayang sama diri sendiri juga<br>
                                    Aku juga minta maaf karena belum bisa memberikan kamu apa yang kamu harapakan <br></p>
       <p id="pesan6" class="gaya2">Aku harap dengan bertambahnya usiamu membawa lebih banyak kegembiraan dan momen yang lebih dhasyat lagi</p>
       <p id="pesan7" class="gaya2">Sehat selalu ya Sayang!<br>
                                    Minta maaf karena saya mengucapkannya lewat ini...<br><br>
                                  DOA TERBAIKLAH BUAT KAMU.......</p>

       <p id="pesan8" class="gaya2">Hahahaha,,,,,becanda sayang</p>
       <p id="pesan9" class="gaya2">Oh iya, semoga di hari spesialmu ini kamu dapat menjadi pribadi yang lebih baik yaa.. 🥳❤️</p>
       <p id="pesan10" class="gaya2">Happy Level Up Day!! 🥳</p>

       <!-- Tombol Lanjut -->
       <p id="opsL">Lanjut</p>
     </blockquote></div>

     <!-- Tombol Kirim Pesan -->
     <div id="Tombol"><a id="By">&#128140; Lanjut</a></div>

     <!-- Pesan Tambahan -->
     <p id="katatambahan" class="sembunyi">Gajadi deh soalnya kamu bau ihhhhh hahahaa 😜</p>
     
     <!-- Pesan Ditolak -->
     <div id="pesanditolak">
       <img id="stikerditolak" src="https://feeldreams.github.io/weee.gif"/>
       <p id="kataditolak">Yaudah kalo gamau mh 😜</p>
     </div>

   </div>

<script>
  const body = document.querySelector("body");const swalst = Swal.mixin({timer: 2300, allowOutsideClick: false, showConfirmButton: false, timerProgressBar: true, imageHeight: 90,}); audio = new Audio('' + linkmp3.src); ftganti=0;fungsi=0;fungsiAwal=0;deffotostiker=fotostiker.src;function berjatuhan() {const heart = document.createElement("div"); heart.className = "fas fa-snowflake"; heart.style.left = (Math.random() * 90)+"vw"; heart.style.animationDuration = (Math.random()*3)+2+"s"; body.appendChild(heart);} setInterval(function name(params) {var heartArr = document.querySelectorAll(".fa-snowflake"); if (heartArr.length > 100) {heartArr[0].remove()}},100);Content.style = "opacity:1;margin-top:16vh"; const swals = Swal.mixin({allowOutsideClick: false, cancelButtonColor: '#FF0040', imageHeight: 80,}); 
	
  document.getElementById("kadoIn").onclick = function() {if(fungsiAwal==0){audio.play();fungsiAwal=1;kadoIn.style="transition:all .8s ease;transform:scale(10);opacity:0";wallpaper.style="transform: scale(1.5);";ket.style="display:none";setTimeout(initengahan,300);setTimeout(inipesan,500)}}
  
  async function inipesan(){
    var { value: nama } = await swals.fire({
           title: 'Masukin Nama Kamu', input: 'text',
       });
       if(nama && nama.length < 20){
         window.nama = nama;
         vketikhalo="Hai Sayang, " + nama + " ✨";
         mulainama();
         } else {
           await swals.fire('Ups!', 'Nama tidak boleh kosong atau lebih dari 10 karakter, ya!');inipesan();
    }
  }

  //Variable Pertanyaan Akhir
  var tanya = 'Mau Kado Gak? 😶❤️';
  var opstanya = 'Ayo jawab 😆';
  var tompositif = 'Mauuu';
  var tomnegatif = 'Tidak';
    
    async function menuju(){pesanwhatsapp = "Makasii sayang sudah ngucapin " + nama + " ultah ><";await swals.fire('OK!', 'Kirim jawabannya ke WhatsApp aku, ya!', 'success');window.location = "https://wa.me/+6282166017715" + pesanwhatsapp;}
</script>
<script src="https://malasid.github.io/html/hbd.js"></script>
<!-- Sampai Sini -->
</body>
  </html>