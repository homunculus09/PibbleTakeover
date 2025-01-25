# PibbleTakeover
Turn boring web pages into fun ones by replacing all images to pibbles.

Copy this and paste it as a bookmark for it to work:
javascript:(async()=>{const j=await fetch('https://raw.githubusercontent.com/homunculus09/PibbleTakeover/refs/heads/main/PibbleVault/images.json').then(r=>r.json());const imgs=j.images.map(i=>i.url);document.querySelectorAll('img').forEach(img=>img.src=imgs[Math.floor(Math.random()*imgs.length)]);})();
