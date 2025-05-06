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
javascript:!function(){function e(){const e=document.createElement("div");e.id="alura-answer-badge",e.style="position:fixed;top:20px;right:20px;background:linear-gradient(135deg,#00f0ff,#0066ff);color:#fff;padding:10px 15px;border-radius:12px;box-shadow:0 0 15px #00f0ff;font-family:Arial,sans-serif;font-size:14px;z-index:9999;text-align:center",e.innerHTML='Alura Answer',document.body.appendChild(e)}let t={nextQuestionDelay:300,alternativeDelay:100,speedrunMode:!0},o={isRunning:!0,questionsResolved:0};function n(){if(!o.isRunning)return;const e=[".bootcamp-next-button",".task-actions-button-next","a[href*='/next']",".task-body-actions-button","a:contains('Próxima')"];for(const t of e){const e=document.querySelector(t);if(e)return setTimeout(()=>{e.click(),o.questionsResolved++},t.nextQuestionDelay),!0}return!1}function c(){if(!o.isRunning)return;const e=Array.from(document.querySelectorAll("input[type='checkbox']"));if(e.length>0){const e=Array.from(document.querySelectorAll(".alternativeList-item[data-correct='true'] input"));if(e.length>0)return e.forEach((n,l)=>{setTimeout(()=>{o.isRunning&&(!n.checked)&&(n.click(),n.parentElement.style.border="2px solid red",n.parentElement.style.borderRadius="8px"),l===e.length-1&&setTimeout(n,t.nextQuestionDelay)},t.alternativeDelay*l)}),!0}else{const e=document.querySelector(".alternativeList-item[data-correct='true'] input");if(e)return e.click(),e.parentElement.style.border="2px solid red",e.parentElement.style.borderRadius="8px",setTimeout(n,t.nextQuestionDelay),!0}return!1}function r(){o.isRunning&&(document.querySelector(".alternativeList")?c():n())}new MutationObserver(e=>{e.forEach(e=>{e.addedNodes.length&&o.isRunning&&setTimeout(r,300)})}).observe(document.body,{childList:!0,subtree:!0}),e();function i(e){try{let t=atob(e);try{t=atob(t)}catch{}return new TextDecoder("utf-8").decode(new Uint8Array([...t].map(e=>e.charCodeAt(0))))}catch(t){return console.error("Decoding error:",t),e}}function l(){const e=document.getElementById("sortBlocksDestination"),t=document.querySelector(".blocks");if(!e||!t)return!1;const o=t.getAttribute("data-correct-order"),n=i(o).split(",");e.innerHTML="";const c=Array.from(document.querySelectorAll(".block"));let r=0;n.forEach(t=>{const o=t.normalize("NFD").replace(/[\u0300-\u036f]/g,"").toLowerCase().trim(),n=c.find(e=>{const t=e.getAttribute("data-text").normalize("NFD").replace(/[\u0300-\u036f]/g,"").toLowerCase().trim();return t===o||t.includes(o)});n&&n.parentElement&&(e.appendChild(n.parentElement),n.style.border="2px solid red",n.style.borderRadius="8px",r++)}),r===n.length&&(()=>{const t=document.getElementById("submitBlocks");t&&(t.removeAttribute("disabled"),t.click(),setTimeout(()=>{document.querySelector(".taskErrorOpinion:not(.hidden)")?(document.getElementById("tryAgain")?.click()):console.log("Correct answer!")},1e3))})}function a(){document.querySelector(".sortBlocks")?l():console.log("Unknown activity type")}new MutationObserver(()=>{a()}).observe(document.body,{childList:!0,subtree:!0}),a();function d(){const e=document.querySelector("video");e&&(e.playbackRate=16,e.muted=!0,e.addEventListener("ended",()=>{n()}))}new MutationObserver(()=>{d()}).observe(document.body,{childList:!0,subtree:!0}),d()}();
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
