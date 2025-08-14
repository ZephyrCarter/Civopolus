
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
let eitherOr = Math.floor(Math.random() * 2);
let warOrPeace;
if (eitherOr >= 1) {
  warOrPeace = "Join!";
} else {
  warOrPeace = "No!";
}

document.getElementById("join_no").innerHTML = warOrPeace;
</script>
    
  <hr>

  <h2>(Peace) Contactor becomes king?</h2>

<h3 id="contkingyes_no"></h3>
<script>
let eitherOr = Math.floor(Math.random() * 2);
let warOrPeace;
if (eitherOr >= 1) {
  warOrPeace = "No!";
} else {
  warOrPeace = "Yes!";
}

document.getElementById("contkingyes_no").innerHTML = warOrPeace;
</script>
    
  <hr>

<h2>(War) Who attacks first, one who contacter or contacted?</h2>

<h3 id="uattack_theyattack"></h3>
<script>
let eitherOr = Math.floor(Math.random() * 2);
let warOrPeace;
if (eitherOr >= 1) {
  warOrPeace = "Contactor!";
} else {
  warOrPeace = "Contactee!";
}

document.getElementById("uattack_theyattack").innerHTML = warOrPeace;
</script>
 <hr>

<h2>(War) Kill or no kill?</h2>

<h3 id="kill_no"></h3>
<script>
let eitherOr = Math.floor(Math.random() * 2);
let warOrPeace;
if (eitherOr >= 1) {
  warOrPeace = "Kill!";
} else {
  warOrPeace = "Failed kill!";
}

document.getElementById("kill_no").innerHTML = warOrPeace;
</script>

  <hr>

<h2>(kill) Killer: continue with attack, or stay in place?</h2>

<h3 id="continue_stay"></h3>
<script>
let eitherOr = Math.floor(Math.random() * 2);
let warOrPeace;
if (eitherOr >= 1) {
  warOrPeace = "Continue!";
} else {
  warOrPeace = "Stay!";
}

document.getElementById("continue_stay").innerHTML = warOrPeace;
</script>

<hr>

<hr>


















