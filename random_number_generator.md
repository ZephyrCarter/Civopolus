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



















