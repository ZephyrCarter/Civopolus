<title>Civopolus: Manor</title>
   <link rel="icon" type="image/x-icon" href="favicon.ico">

<style>

body {
background-color: black;
text-align: center;
color: white;  
}
.greeting {border-color: white;
		  border-style: solid;}
</style>

<h1 class="greeting">Numbers randomly generated</h1>
  
<hr>
<hr>

<iframe width="560" height="315" src="https://www.youtube.com/embed/hbe3CQamF8k?si=we0ZEZB_ORcFs4Gc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<hr>
<hr>

<h2>War or Peace?</h2>

<h3 id="war_peace"></h3>
<script>
let eitherOr = Math.floor(Math.random() * 2);
let warOrPeace;
if (eitherOr >= 1) {
  warOrPeace = "War!";
} else {
  warOrPeace = "Peace!";
}

document.getElementById("war_peace").innerHTML = warOrPeace;
</script>
  <hr>
  
<h2>(Peace) Join kingdom or no?</h2>

<h3 id="join_no"></h3>
<script>
let joinchoice = Math.floor(Math.random() * 2);
let join;
if (joinchoice >= 1) {
  join = "Join!";
} else {
  join = "No!";
}

document.getElementById("join_no").innerHTML = join;
</script>
    
  <hr>

  <h2>(Peace) Contactor becomes king?</h2>

<h3 id="contkingyes_no"></h3>
<script>
let kingchoice = Math.floor(Math.random() * 2);
let king;
if (kingchoice >= 1) {
  king = "No!";
} else {
  king = "Yes!";
}

document.getElementById("contkingyes_no").innerHTML = king;
</script>
    
  <hr>

<h2>(War) Who attacks first, one who contacter or contacted?</h2>

<h3 id="uattack_theyattack"></h3>
<script>
let uattackchoice = Math.floor(Math.random() * 2);
let uattack;
if (uattackchoice >= 1) {
  uattack = "Contactor!";
} else {
  uattack = "Contactee!";
}

document.getElementById("uattack_theyattack").innerHTML = uattack;
</script>
 <hr>

<h2>(War) Kill or no kill?</h2>

<h3 id="kill_no"></h3>
<script>
let killnochoice = Math.floor(Math.random() * 2);
let killno;
if (killnochoice >= 1) {
  killno = "Kill!";
} else {
  killno = "Failed kill!";
}

document.getElementById("kill_no").innerHTML = killno;
</script>

  <hr>

<h2>(kill) Killer: continue with attack, or stay in place?</h2>

<h3 id="continue_stay"></h3>
<script>
let continuechoice = Math.floor(Math.random() * 2);
let contstay;
if (continuechoice >= 1) {
  contstay = "Continue!";
} else {
  contstay = "Stay!";
}

document.getElementById("continue_stay").innerHTML = contstay;
</script>

<hr>
<hr>

<h6><i>Note: Although this video or videos are integrated on this site using the "embed" feature from youtube, I neither own nor take credit for their music, as dope as it it.</i></h6>
 
<hr>
<hr>

















