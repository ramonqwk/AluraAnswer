<a href="#"><img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=150&color=ff4fcf&text=Alura%20Answer&fontSize=40&fontAlignY=33&fontColor=ffffff"/></a>

<div align="center">
  <img src="https://i.imgur.com/wzkJWed_d.png?maxwidth=520&shape=thumb&fidelity=high" width="100px" alt="Alura Logo"/>
</div>

<h2 align="center"><strong>Alura Answer</strong></h2>

<p align="center" style="font-size: 16px;">
  O <strong>Alura Answer</strong> realiza automaticamente as <strong>atividades</strong> na plataforma <strong>Alura</strong>, poupando seu tempo e esforço.
</p>

<p align="center"><strong>Para usar, copie o código abaixo:</strong></p>

<div align="center">

<pre>
<code>
javascript:(function(){let b=document.body.appendChild(document.createElement('div'));b.id='alura-answer-badge';b.textContent='Alura Answer';Object.assign(b.style,{position:'fixed',top:'20px',right:'20px',background:'linear-gradient(135deg,#00f0ff,#0066ff)',color:'#fff',padding:'10px',borderRadius:'12px',boxShadow:'0 0 10px #00f0ff',fontSize:'14px',zIndex:9999});const c={n:1000,a:200},r=1;function clickNext(){if(!r)return;for(let s of['.bootcamp-next-button','.task-actions-button-next','.task-body-actions-button']){let e=document.querySelector(s);if(e)return setTimeout(()=>e.click(),c.n),!0;}let l=Array.from(document.querySelectorAll('a')).find(a=>/Próxima/i.test(a.textContent));if(l)return setTimeout(()=>l.click(),c.n),!0;}function clickAlt(){if(!r)return;let o=document.querySelectorAll(".alternativeList-item[data-correct='true'] input");if(!o.length)return;Array.from(o).forEach((e,i)=>setTimeout(()=>{if(!e.checked)e.click();if(i+1===o.length)setTimeout(clickNext,c.n)},c.a*i));}function step(){document.querySelector('.alternativeList')?clickAlt():clickNext()}new MutationObserver(step).observe(document.body,{childList:1,subtree:1});step();function sortBlocks(){let e=document.getElementById('sortBlocksDestination'),t=document.querySelector('.blocks');if(!e||!t)return;let ord=atob(atob(t.getAttribute('data-correct-order'))).split(','),bl=Array.from(document.querySelectorAll('.block'));e.innerHTML='';ord.map(x=>x.normalize('NFD').replace(/[\u0300-\u036f]/g,'').toLowerCase().trim()).forEach(term=>{let m=bl.find(b=>b.getAttribute('data-text').normalize('NFD').replace(/[\u0300-\u036f]/g,'').toLowerCase().includes(term));m&&(e.appendChild(m.parentElement),m.style.border='2px solid red')});let btn=document.getElementById('submitBlocks');btn&&setTimeout(()=>btn.click(),c.n);}new MutationObserver(sortBlocks).observe(document.body,{childList:1,subtree:1});sortBlocks();})();
</code>
</pre>

</div>

<p align="center">
<sub><i>Clique abaixo para entrar no servidor do Discord ou doar</i></sub>
</p>

<p align="center">
    <a href="https://discord.gg/cZVtWmWsUE"><img width="15%" alt="Discord (CS)" title="Discord (Alura Answer)" src="https://i.imgur.com/r0YUgMR.png"/></a>
  &nbsp;
    <a href="https://pixgg.com/Ramon"><img width="15%" alt="Doar" title="Doar" src="https://i.imgur.com/yLUUqaa.png"/></a>
</p>

<p align="center">
  <a href="#"><img src="https://komarev.com/ghpvc/?username=Ramonqwk&style=for-the-badge&label=Views:&color=gray"/></a>
</p>

<!-- Créditos -->
<div align="center">
  <img src="https://i.imgur.com/gi0h7c1.jpeg" width="150px" alt="Ramon Profile"/>
  <h3 style="color: #e86a04; animation: pulse 2s infinite;">Criado por Ramon!</h3>
</div>

<a href="#"><img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=150&color=ffffff&section=footer"/></a>
