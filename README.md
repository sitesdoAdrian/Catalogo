<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="theme-color" content="#080707">
<title>Catálogo | @l.cartomante.l</title>
<style>
:root{--bg:#080707;--line:#3a2d2d;--muted:#b8b0ad;--white:#f6f0ec}
*{box-sizing:border-box}
body{margin:0;background:radial-gradient(ellipse at top,#291216 0,#080707 60%);color:var(--white);font-family:Georgia,'Times New Roman',serif}
main{max-width:900px;margin:auto;padding:18px 14px 120px}
.hero{border:1px solid #4a3a3a;border-radius:20px;text-align:center;padding:25px 18px;background:linear-gradient(145deg,#1d1717,#0c0a0a)}
.orn{color:#c5aeb5;letter-spacing:6px;font-size:13px}
.hero h1{font-size:clamp(28px,7.5vw,46px);margin:12px 0;color:#ece3dd;letter-spacing:3px}
.hero p{color:#c5b9b5;font-style:italic}
.flor-lotus{display:block;width:100%;max-width:390px;height:230px;object-fit:cover;object-position:center;margin:20px auto 5px;border-radius:14px;border:1px solid #5a4548;filter:sepia(12%) brightness(.88)}
.insta-btn{display:inline-flex;gap:8px;margin-top:16px;padding:10px 20px;border-radius:999px;background:linear-gradient(135deg,#833ab4,#fd1d1d,#f77737);color:#fff;text-decoration:none;font:700 13px Arial,sans-serif}
h2{margin:30px 0 14px;padding:11px 14px;text-align:center;border:1px solid #5a4a48;border-radius:12px;background:linear-gradient(90deg,#100e0e,#2a181b,#100e0e);font-size:16px;letter-spacing:2px;text-transform:uppercase}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:14px}
.item{border:1px solid var(--line);border-radius:16px;overflow:hidden;background:linear-gradient(145deg,#1e1818,#120e0e);display:flex;flex-direction:column}
.img-wrap{position:relative;height:165px;background:#0f0c0c;overflow:hidden;cursor:pointer;display:block}
.img-wrap img{width:100%;height:100%;object-fit:cover;display:block}
.img-edit{position:absolute;inset:0;display:grid;place-items:center;background:#0008;opacity:0;transition:.2s;font:12px Arial,sans-serif;color:#fff}
.img-wrap:hover.img-edit,.img-wrap:focus-within.img-edit{opacity:1}
.content{padding:14px;display:flex;flex-direction:column;gap:8px;flex:1}
.top{display:flex;justify-content:space-between;align-items:flex-start;gap:10px}
.item h3{margin:0;font-size:18px;color:#f0e6e0}
.price{background:#ffffff10;border-radius:999px;padding:4px 10px;font:700 13px Arial,sans-serif;color:#f5dfe0;white-space:nowrap}
.desc{font:13px/1.6 Arial,sans-serif;color:var(--muted);flex:1}
.phase{font:11px/1.6 Arial,sans-serif;color:#c97a7e;background:#c97a7e18;border:1px dashed #c97a7e55;padding:8px;border-radius:6px;white-space:pre-line}
.add{border:1px solid #7a4a4f;border-radius:10px;padding:11px;background:linear-gradient(180deg,#5a2229,#3d151a);color:#fff8f6;font-weight:700;font-size:13.5px;cursor:pointer}
.add.ok{background:#2a4a2a;border-color:#4a6a4a}
.info{margin-top:28px;border:1px solid var(--line);border-radius:14px;padding:20px;background:#151111}
.info ul{padding-left:20px;font:14px/1.7 Arial,sans-serif;color:var(--muted)}
.note{font:12px/1.6 Arial,sans-serif;color:#9f9592;background:#ffffff06;border-radius:8px;padding:10px 12px;margin-top:12px}
.cartbar{position:fixed;z-index:10;bottom:0;left:0;right:0;display:flex;justify-content:space-between;align-items:center;gap:12px;padding:12px 14px;background:#0a0808f0;border-top:1px solid #4a3838;backdrop-filter:blur(12px)}
.cartcount{font:13px Arial,sans-serif;color:#ddd}
.checkout{border:0;border-radius:11px;padding:13px 18px;background:linear-gradient(180deg,#e8ddd8,#c9bbb6);color:#1a1212;font-weight:800;cursor:pointer}
.checkout:disabled{opacity:.5;cursor:not-allowed}
#toast{position:fixed;left:50%;bottom:90px;transform:translateX(-50%) translateY(20px);background:#1e1515;border:1px solid #5a4040;color:#f0e0de;padding:10px 16px;border-radius:999px;font:13px Arial,sans-serif;opacity:0;pointer-events:none;transition:.35s;z-index:20;max-width:90%;text-align:center}
#toast.show{opacity:1;transform:translateX(-50%) translateY(0)}
.footer{text-align:center;color:#8a7f7c;font:12px Arial,sans-serif;margin:28px 0 10px}
.footer a{color:#e8a0a6;text-decoration:none;font-weight:700}
@media(max-width:520px){.grid{grid-template-columns:1fr}.flor-lotus{height:210px}.cartbar{padding:10px}.checkout{padding:12px;font-size:12px}}
</style>
</head>
<body>
<main>
<header class="hero">
<div class="orn">☾ ✦ ♱ ✦ ☽</div>
<h1>TABELA DE PREÇOS</h1>
<p>Gratidão pela sua confiança!</p>
<img class="flor-lotus" src="https://uploads.onecompiler.io/454bxpyrs/1791597926115/IMG-20261009-WA0017.jpg" alt="Flor de lótus branca">
<a class="insta-btn" href="https://www.instagram.com/l.cartomante.l" target="_blank" rel="noopener noreferrer">✦ @l.cartomante.l no Instagram</a>
</header>
<h2>✧ Consultas Básicas ✧</h2>
<div class="grid" id="grid-basicas"></div>
<h2>✧ Consultas Especiais ✧</h2>
<div class="grid" id="grid-especiais"></div>
<section class="info">
<h2>✧ Como Pedir ✧</h2>
<ul>
<li>Adicione as consultas ao carrinho.</li>
<li>Confira o valor total do pedido.</li>
<li>Ao finalizar, o WhatsApp abrirá com as consultas e as perguntas para você preencher ou responder.</li>
<li>Toque na foto de cada consulta para trocá-la por uma imagem sua.</li>
</ul>
<p class="note">Tiragens para reflexão e entretenimento.</p>
</section>
<p class="footer">✦ <a href="https://www.instagram.com/l.cartomante.l" target="_blank" rel="noopener noreferrer">@l.cartomante.l</a> ✦</p>
</main>
<div class="cartbar"><span id="count" class="cartcount">Carrinho vazio</span><button id="btnCheckout" class="checkout" onclick="checkout()">🛒 Pedir pelo WhatsApp</button></div>
<div id="toast" role="status" aria-live="polite"></div>
<script>
const phone='5585989882369';
const produtos=[
{id:'1pergunta',nome:'1 pergunta',preco:5,cat:'basicas',desc:'Uma pergunta direta sobre uma dúvida específica.',fase:'Digite sua pergunta + contexto:',img:'https://uploads.onecompiler.io/454bxpyrs/1791597926115/IMG-20261009-WA0017.jpg'},
{id:'2perguntas',nome:'2 perguntas',preco:10,cat:'basicas',desc:'Duas perguntas diferentes, envie numeradas.',fase:'Pergunta 1:\nPergunta 2:\nContexto geral:',img:'https://uploads.onecompiler.io/454bxpyrs/1791597926115/IMG-20261009-WA0017.jpg'},
{id:'3perguntas',nome:'3 perguntas',preco:15,cat:'basicas',desc:'Três dúvidas ou aspectos de um assunto.',fase:'Pergunta 1:\nPergunta 2:\nPergunta 3:\nContexto:',img:'https://images.unsplash.com/photo-1544365558-35aa4afcf11f?w=600&auto=format&fit=crop'},
{id:'3simnao',nome:'3 Sim ou Não',preco:7,cat:'basicas',desc:'Três perguntas de sim ou não.',fase:'1 - (Sim/Não):\n2 - (Sim/Não):\n3 - (Sim/Não):',img:'https://uploads.onecompiler.io/454bxpyrs/1791597926115/IMG-20261009-WA0017.jpg'},
{id:'conselho',nome:'Conselho',preco:3,cat:'basicas',desc:'Mensagem de orientação para refletir.',fase:'Tema que quer conselho:',img:'https://images.unsplash.com/photo-1506126613408-eca07ce68773?w=600&auto=format&fit=crop'},
{id:'mensal',nome:'Mensal',preco:15,cat:'especiais',desc:'Tendências e conselhos para o mês.',fase:'Mês que quer saber (ex.: novembro):\nFoco principal:',img:'https://images.unsplash.com/photo-1532012197267-da84d127e765?w=600&auto=format&fit=crop'},
{id:'devofazer',nome:'Devo fazer isso?',preco:10,cat:'especiais',desc:'Para refletir sobre uma decisão.',fase:'Situação:\nO que está pensando em fazer:',img:'https://images.unsplash.com/photo-1490735891913-40897cdaafd1?w=600&auto=format&fit=crop'},
{id:'ex',nome:'Tiragem de Ex',preco:10,cat:'especiais',desc:'Sobre relação passada e reflexão.',fase:'Nome ou inicial do ex (opcional):\nO que quer saber:',img:'https://images.unsplash.com/photo-1516589178581-6cd7833ae3b2?w=600&auto=format&fit=crop'},
{id:'templo',nome:'Templo do Diabo',preco:15,cat:'especiais',desc:'Para explorar desejos, desafios e limites.',fase:'Tema ou desejo que quer explorar:',img:'https://uploads.onecompiler.io/454bxpyrs/1791597926115/IMG-20261009-WA0017.jpg'}
];
let cart=[];
try{const salvo=JSON.parse(localStorage.getItem('tarot_cart')||'[]');if(Array.isArray(salvo)){cart=salvo.filter(item=>item&&typeof item.nome==='string'&&Number.isFinite(item.preco)&&typeof item.fase==='string');}}catch(e){cart=[]}
let imagensSalvas={};
try{const fotos=JSON.parse(localStorage.getItem('tarot_imgs')||'{}');if(fotos&&typeof fotos==='object'&&!Array.isArray(fotos)){imagensSalvas=fotos;}}catch(e){imagensSalvas={}}
function money(n){return n.toLocaleString('pt-BR',{style:'currency',currency:'BRL'});}
function toast(texto){const el=document.getElementById('toast');el.textContent=texto;el.classList.add('show');setTimeout(()=>{el.classList.remove('show');},2200);}
function save(){try{localStorage.setItem('tarot_cart',JSON.stringify(cart));}catch(e){toast('Não foi possível salvar o carrinho neste navegador.');}renderCart();}
function renderCart(){const total=cart.reduce((s,x)=>s+x.preco,0);document.getElementById('count').textContent=cart.length?`${cart.length} ${cart.length===1?'item':'itens'} • ${money(total)}`:'Carrinho vazio';document.getElementById('btnCheckout').disabled=!cart.length;}
function addItem(id,btn){const produto=produtos.find(x=>x.id===id);if(!produto)return;cart.push({id:produto.id,nome:produto.nome,preco:produto.preco,fase:produto.fase});save();toast(`${produto.nome} adicionado`);btn.textContent='✓ Adicionado';btn.classList.add('ok');setTimeout(()=>{btn.textContent='＋ Adicionar ao carrinho';btn.classList.remove('ok');},1200);}
function handleImage(input,id){const arquivo=input.files&&input.files[0];if(!arquivo)return;if(!arquivo.type.startsWith('image/')){toast('Escolha um arquivo de imagem.');return;}if(arquivo.size>3*1024*1024){toast('Escolha uma imagem de até 3 MB.');return;}const leitor=new FileReader();leitor.onload=e=>{try{imagensSalvas[id]=e.target.result;localStorage.setItem('tarot_imgs',JSON.stringify(imagensSalvas));const img=document.querySelector(`img[data-id="${id}"]`);if(img)img.src=e.target.result;toast('Foto trocada neste navegador!');}catch(erro){toast('Imagem muito grande para salvar. Use uma foto menor.');}};leitor.readAsDataURL(arquivo);}
function renderProdutos(){const basicas=document.getElementById('grid-basicas');const especiais=document.getElementById('grid-especiais');produtos.forEach(p=>{const imagem=imagensSalvas[p.id]||p.img;const card=document.createElement('article');card.className='item';const label=document.createElement('label');label.className='img-wrap';const foto=document.createElement('img');foto.dataset.id=p.id;foto.src=imagem;foto.alt='Foto de '+p.nome;foto.loading='lazy';foto.onerror=function(){this.onerror=null;this.src='https://images.unsplash.com/photo-1490750967868-88aa4486c946?w=600&auto=format&fit=crop';};const editar=document.createElement('span');editar.className='img-edit';editar.textContent='📷 Trocar foto';const input=document.createElement('input');input.type='file';input.accept='image/*';input.hidden=true;input.addEventListener('change',function(){handleImage(this,p.id);});label.append(foto,editar,input);const conteudo=document.createElement('div');conteudo.className='content';const topo=document.createElement('div');topo.className='top';const titulo=document.createElement('h3');titulo.textContent=p.nome;const preco=document.createElement('span');preco.className='price';preco.textContent=money(p.preco);topo.append(titulo,preco);const descricao=document.createElement('p');descricao.className='desc';descricao.textContent=p.desc;const fase=document.createElement('div');fase.className='phase';fase.textContent='📝 '+p.fase;const botao=document.createElement('button');botao.className='add';botao.textContent='＋ Adicionar ao carrinho';botao.type='button';botao.addEventListener('click',function(){addItem(p.id,this);});conteudo.append(topo,descricao,fase,botao);card.append(label,conteudo);if(p.cat==='basicas'){basicas.appendChild(card);}else{especiais.appendChild(card);}});}
function checkout(){if(!cart.length){toast('Adicione uma consulta ao carrinho.');return;}const total=cart.reduce((s,x)=>s+x.preco,0);let mensagem='Olá! Vim pelo catálogo @l.cartomante.l e quero fazer este pedido:\n\n';cart.forEach((item,indice)=>{mensagem+=`--- ${indice+1}º ITEM: ${item.nome.toUpperCase()} ---\nPreço: ${money(item.preco)}\n${item.fase}\n\n`;});mensagem+=`TOTAL: ${money(total)}\nInstagram: @l.cartomante.l - https://www.instagram.com/l.cartomante.l`;const link='https://wa.me/'+phone+'?text='+encodeURIComponent(mensagem);window.open(link,'_blank');}
renderProdutos();renderCart();
</script>
</body>
</html>