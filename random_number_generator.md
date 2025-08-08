
<style>

body {

text-align: center;
  
}
  
</style>

<h1>Numbers randomly generated</h1>
  
  <hr>

<h2>War or Peace? 1=yes 2=no</h2>

<h3 id="warOrPeace"></h3>

<script>
document.getElementById("warOrPeace").innerHTML =
Math.floor(Math.random() * 3);
</script>
    
  <hr>

<h2>Who attacks first, one who contacter contacted? 1=contacter 2=contacted</h2>

<h3 id="whoAttack"></h3>

<script>
document.getElementById("whoAttack").innerHTML =
Math.floor(Math.random() * 3);
</script>

  <hr>

<h2>If war: killed? 1=yes 2=no</h2>

<h3 id="killOrNo"></h3>

<script>
document.getElementById("killOrNo").innerHTML =
Math.floor(Math.random() * 3);
</script>
  
  <hr>

<h2>Killer: continue with attack, or stay in place</h2>

<h3 id="killerMoveOrNo"></h3>

<script>
document.getElementById("killerMoveOrNo").innerHTML =
Math.floor(Math.random() * 3);
</script>























