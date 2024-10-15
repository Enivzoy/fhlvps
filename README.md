# fhlvps
Aw shucks! looks like [fml](https://discord.gg/ANTtxXnQuZ) isnt offering free hosting anymore!  
aw fuck! what can me! a reverse engineer possibly do?!!  
  
*rolls coinslot machine*  
HOLY SHIT!  
I ACTUALLY WON!!!!!!!!!!!!!  
  
  
paste into javascript console at   
https://fmhl.devloo.xyz/ad-program/index.php  
```js
alert("Earns you coins every 1 second enjoy");alert("this is fucking illegal!!!! and im not one to stop you\nconsider supporting the devs by watching the ads or smth but you do you mans\nLove from Enivzoy <3");setInterval(()=>{var w=new XMLHttpRequest();w.open("POST","",true);w.setRequestHeader("Content-Type","application/x-www-form-urlencoded");w.onreadystatechange=function (){if(w.readyState===4 && w.status===200){var z=JSON.parse(w.responseText);if(z.success){document.getElementById('pointsDisplay').textContent=z.points;}else{document.getElementById('alert-container').innerHTML='<div class="alert alert-dark">'+z.error+'</div>';}}};w.send("updatePoints=1");},1000);
```
