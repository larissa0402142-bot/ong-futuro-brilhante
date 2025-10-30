# Ong-futuro-brilhante-
A ONG Futuro Brilhante tem como objetivo principal promover a transformação social por meio da educação, solidariedade e inclusão digital. Nosso propósito é oferecer oportunidades reais de crescimento para crianças, jovens e famílias em situação de vulnerabilidade, capacitando-os para o mercado de trabalho e fortalecendo o senso de cidadania.

ONG Futuro Brilhante — Projeto Web (HTML5, CSS3, JavaScript)

https://ong-futuro-brilhante.vercel.app/


> Conteúdo pronto para colar no VSCode. Estrutura de pastas sugerida no final.




---

Arquivos

1) index.html

<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>ONG Futuro Brilhante — Início</title>
  <meta name="description" content="ONG Futuro Brilhante: educação, solidariedade e inclusão. Participe!">
  <link rel="stylesheet" href="/css/styles.css">
</head>
<body>
  <header class="site-header" role="banner">
    <div class="container header-inner">
      <a href="/index.html" class="logo" aria-label="ONG Futuro Brilhante">
        <img src="/assets/logo.png" alt="Logotipo ONG Futuro Brilhante" width="120" height="60">
      </a>
      <nav class="main-nav" role="navigation" aria-label="Menu principal">
        <button id="navToggle" aria-expanded="false" aria-controls="navList">Menu</button>
        <ul id="navList" class="nav-list">
          <li><a href="/index.html">Início</a></li>
          <li><a href="/projetos.html">Projetos</a></li>
          <li><a href="/cadastro.html">Cadastro</a></li>
          <li><a href="#contato">Contato</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <main>
    <section class="hero" aria-label="Seção principal">
      <div class="container">
        <h1>Iluminando caminhos, inspirando sonhos</h1>
        <p class="lead">A ONG Futuro Brilhante promove oportunidades educacionais, inclusão digital e apoio a famílias em situação de vulnerabilidade.</p>
        <div class="cta-row">
          <a class="btn primary" href="/projetos.html">Conheça nossos projetos</a>
          <a class="btn outline" href="/cadastro.html">Participe como voluntário</a>
        </div>
      </div>
    </section>

    <section class="about container" aria-labelledby="about-title">
      <h2 id="about-title">Nosso objetivo</h2>
      <p>Promover a transformação social por meio da educação, solidariedade e inclusão digital, capacitando crianças, jovens e famílias para um futuro mais justo.</p>
      <ul class="features">
        <li>
          <h3>Educação</h3>
          <p>Programas de reforço escolar e alfabetização digital.</p>
        </li>
        <li>
          <h3>Voluntariado</h3>
          <p>Oportunidades práticas para quem quer ajudar.</p>
        </li>
        <li>
          <h3>Doações</h3>
          <p>Campanhas transparentes com relatórios de impacto.</p>
        </li>
      </ul>
    </section>

    <section class="impact container" aria-labelledby="impact-title">
      <h2 id="impact-title">Nossos números</h2>
      <div class="stats">
        <div>
          <strong>+120</strong>
          <span>beneficiados por mês</span>
        </div>
        <div>
          <strong>+35</strong>
          <span>projetos realizados</span>
        </div>
        <div>
          <strong>+200</strong>
          <span>voluntários engajados</span>
        </div>
      </div>
    </section>

    <section id="contato" class="contact container" aria-labelledby="contact-title">
      <h2 id="contact-title">Contato</h2>
      <p>Tem interesse em ajudar ou deseja mais informações? Entre em contato.</p>
      <address>
        <p>email: <a href="mailto:contato@ongfuturobrilhante.org">contato@ongfuturobrilhante.org</a></p>
        <p>telefone: <a href="tel:+550000000000">(00) 00000-0000</a></p>
      </address>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container">
      <p>&copy; <span id="year"></span> ONG Futuro Brilhante — Todos os direitos reservados.</p>
      <p class="small">Transparência · Privacidade · Acessibilidade</p>
    </div>
  </footer>

  <script src="/js/main.js" defer></script>
</body>
</html>


---

2) projetos.html

<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Projetos — ONG Futuro Brilhante</title>
  <link rel="stylesheet" href="/css/styles.css">
</head>
<body>
  <header class="site-header">
    <div class="container header-inner">
      <a href="/index.html" class="logo"><img src="/assets/logo.png" alt="logo"></a>
      <nav class="main-nav">
        <ul class="nav-list">
          <li><a href="/index.html">Início</a></li>
          <li><a href="/projetos.html">Projetos</a></li>
          <li><a href="/cadastro.html">Cadastro</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <main class="container">
    <h1>Projetos Sociais</h1>
    <p>Conheça os projetos em andamento e como você pode ajudar.</p>

    <section class="project-list" aria-live="polite">
      <article class="project-card">
        <img src="/assets/projeto-educacao.jpg" alt="Projeto Educação">
        <h2>Projeto Educação Digital</h2>
        <p>Oficinas de informática, alfabetização digital e preparação para o mercado de trabalho.</p>
        <a class="btn" href="/cadastro.html">Quero participar</a>
      </article>

      <article class="project-card">
        <img src="/assets/projeto-alimentacao.jpg" alt="Projeto Alimentação">
        <h2>Projeto Segurança Alimentar</h2>
        <p>Distribuição de cestas básicas e hortas comunitárias.</p>
        <a class="btn" href="#">Doar</a>
      </article>

    </section>
  </main>

  <footer class="site-footer">
    <div class="container">
      <p>&copy; <span id="year2"></span> ONG Futuro Brilhante</p>
    </div>
  </footer>
  <script src="/js/main.js" defer></script>
</body>
</html>


---

3) cadastro.html (formulário com validação HTML5 e máscaras via JS)

<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Cadastro — ONG Futuro Brilhante</title>
  <link rel="stylesheet" href="/css/styles.css">
</head>
<body>
  <header class="site-header">
    <div class="container header-inner">
      <a href="/index.html" class="logo"><img src="/assets/logo.png" alt="logo"></a>
      <nav class="main-nav">
        <ul class="nav-list">
          <li><a href="/index.html">Início</a></li>
          <li><a href="/projetos.html">Projetos</a></li>
          <li><a href="/cadastro.html">Cadastro</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <main class="container">
    <h1>Cadastro de Voluntário / Doador</h1>

    <form id="cadastroForm" novalidate>
      <fieldset>
        <legend>Dados pessoais</legend>

        <label for="nome">Nome completo</label>
        <input id="nome" name="nome" type="text" required minlength="3" placeholder="Nome completo">

        <label for="email">E‑mail</label>
        <input id="email" name="email" type="email" required placeholder="seu@exemplo.com">

        <label for="cpf">CPF</label>
        <input id="cpf" name="cpf" type="text" inputmode="numeric" pattern="\d{3}\.\d{3}\.\d{3}-\d{2}" required placeholder="000.000.000-00">

        <label for="telefone">Telefone</label>
        <input id="telefone" name="telefone" type="tel" inputmode="tel" required placeholder="(00) 00000-0000">

        <label for="nascimento">Data de nascimento</label>
        <input id="nascimento" name="nascimento" type="date" required>

      </fieldset>

      <fieldset>
        <legend>Endereço</legend>
        <label for="cep">CEP</label>
        <input id="cep" name="cep" type="text" inputmode="numeric" pattern="\d{5}-?\d{3}" placeholder="00000-000" required>

        <label for="endereco">Endereço</label>
        <input id="endereco" name="endereco" type="text" required>

        <label for="cidade">Cidade</label>
        <input id="cidade" name="cidade" type="text" required>

        <label for="estado">Estado</label>
        <select id="estado" name="estado" required>
          <option value="">Selecione</option>
          <option value="SP">SP</option>
          <option value="RJ">RJ</option>
          <option value="MG">MG</option>
          <!-- completar conforme necessário -->
        </select>
      </fieldset>

      <fieldset>
        <legend>Preferências</legend>
        <label>
          <input type="checkbox" name="newsletter" checked>
          Aceito receber novidades por e‑mail
        </label>
      </fieldset>

      <div class="form-actions">
        <button type="submit" class="btn primary">Enviar cadastro</button>
        <button type="reset" class="btn outline">Limpar</button>
      </div>
    </form>
  </main>

  <footer class="site-footer">
    <div class="container">
      <p>&copy; ONG Futuro Brilhante</p>
    </div>
  </footer>

  <script src="/js/main.js" defer></script>
</body>
</html>


---

4) css/styles.css

/* Reset simples */
*{box-sizing:border-box}
html,body{height:100%}
body{font-family:system-ui,-apple-system,Segoe UI,Roboto,'Helvetica Neue',Arial;line-height:1.4;color:#1f2937;margin:0;background:#f7fafc}
.container{max-width:1100px;margin:0 auto;padding:1rem}
.header-inner{display:flex;align-items:center;justify-content:space-between;padding:1rem 0}
.logo img{display:block}
.main-nav .nav-list{list-style:none;margin:0;padding:0;display:flex;gap:1rem}
.main-nav a{color:inherit;text-decoration:none}
.site-header{background:#ffffff;box-shadow:0 1px 2px rgba(0,0,0,.06);position:sticky;top:0;z-index:50}
.hero{padding:4rem 0;background:linear-gradient(180deg,#fff 0%,#f0f9ff 100%);text-align:center}
.hero h1{font-size:clamp(1.6rem,3vw,2.4rem);margin:0 0 .5rem}
.lead{max-width:700px;margin:0 auto 1rem;color:#334155}
.cta-row{display:flex;gap:.5rem;justify-content:center}
.btn{display:inline-block;padding:.6rem 1rem;border-radius:.5rem;border:1px solid transparent;text-decoration:none}
.btn.primary{background:#0ea5a4;color:#fff}
.btn.outline{background:transparent;border-color:#0ea5a4;color:#0ea5a4}
.about{padding:2rem 0}
.features{display:flex;gap:1rem;flex-wrap:wrap;padding:0;list-style:none}
.features li{flex:1 1 200px;background:#fff;padding:1rem;border-radius:.5rem;box-shadow:0 1px 2px rgba(2,6,23,.06)}
.project-list{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:1rem}
.project-card{background:#fff;border-radius:.5rem;padding:1rem;box-shadow:0 1px 4px rgba(2,6,23,.06)}
.project-card img{max-width:100%;height:160px;object-fit:cover;border-radius:.4rem}
.stats{display:flex;gap:1rem;flex-wrap:wrap}
.stats div{background:#fff;padding:1rem;border-radius:.5rem;flex:1 1 140px;text-align:center}
.site-footer{padding:1rem 0;background:#0f172a;color:#fff;margin-top:2rem}
.contact address,a{color:inherit}

/* Form */
form{background:#fff;padding:1rem;border-radius:.5rem;box-shadow:0 1px 4px rgba(2,6,23,.06)}
label{display:block;font-size:.9rem;margin-top:.6rem}
input,select,textarea{width:100%;padding:.6rem;border:1px solid #e2e8f0;border-radius:.4rem}
.form-actions{display:flex;gap:.5rem;margin-top:1rem}
.small{font-size:.85rem;opacity:.9}

/* Responsive nav for small screens */
@media (max-width:700px){
  .main-nav .nav-list{display:none;flex-direction:column;background:#fff;position:absolute;right:1rem;top:64px;padding:1rem;border-radius:.5rem;box-shadow:0 6px 18px rgba(2,6,23,.12)}
  .main-nav .nav-list.show{display:flex}
}

/* Focus states for accessibility */
a:focus,input:focus,button:focus{outline:3px solid rgba(14,165,164,.18);outline-offset:2px}


---

5) js/main.js

// Acessibilidade: atualiza ano do rodapé
document.addEventListener('DOMContentLoaded', function(){
  const year = new Date().getFullYear();
  const y = document.getElementById('year');
  if(y) y.textContent = year;
  const y2 = document.getElementById('year2');
  if(y2) y2.textContent = year;

  // Toggle nav em telas pequenas
  const navToggle = document.getElementById('navToggle');
  const navList = document.getElementById('navList');
  if(navToggle && navList){
    navToggle.addEventListener('click', ()=>{
      const expanded = navToggle.getAttribute('aria-expanded') === 'true';
      navToggle.setAttribute('aria-expanded', String(!expanded));
      navList.classList.toggle('show');
    });
  }

  // Máscaras simples para CPF, telefone e CEP
  function mask(o, f) {
    setTimeout(()=>{
      o.value = f(o.value);
    }, 0);
  }
  function cpfMask(v){
    return v.replace(/\D/g,'').replace(/(\d{3})(\d)/,'$1.$2').replace(/(\d{3})(\d)/,'$1.$2').replace(/(\d{3})(\d{1,2})$/,'$1-$2').slice(0,14);
  }
  function phoneMask(v){
    return v.replace(/\D/g,'').replace(/(\d{2})(\d)/,'($1) ').replace(/(\d{5})(\d)/,'$1-$2').slice(0,15);
  }
  function cepMask(v){
    return v.replace(/\D/g,'').replace(/(\d{5})(\d)/,'$1-$2').slice(0,9);
  }

  const cpf = document.getElementById('cpf');
  const tel = document.getElementById('telefone');
  const cep = document.getElementById('cep');
  if(cpf) cpf.addEventListener('input', e=>mask(e.target, cpfMask));
  if(tel) tel.addEventListener('input', e=>mask(e.target, phoneMask));
  if(cep) cep.addEventListener('input', e=>mask(e.target, cepMask));

  // Validação personalizada (progressive enhancement)
  const form = document.getElementById('cadastroForm');
  if(form){
    form.addEventListener('submit', function(e){
      if(!form.checkValidity()){
        e.preventDefault();
        form.querySelectorAll(':invalid').forEach(el=>{
          el.focus();
        });
        alert('Por favor, preencha corretamente os campos obrigatórios.');
      } else {
        e.preventDefault();
        // Simulação de envio — aqui você pode integrar com API
        alert('Cadastro enviado com sucesso! Obrigado por colaborar.');
        form.reset();
      }
    });
  }
});


---

Sugestão de estrutura de pastas

ong-futuro-brilhante/
├─ index.html
├─ projetos.html
├─ cadastro.html
├─ css/
│  └─ styles.css
├─ js/
│  └─ main.js
└─ assets/
   ├─ logo.png
   ├─ projeto-educacao.jpg
   └─ projeto-alimentacao.jpg


---

Observações finais

Os arquivos são acessíveis, responsivos e usam semântica HTML5.

Serviços externos (pagamentos, banco de dados) devem ser integrados via APIs separadas.

Para publicar no GitHub Pages ou Vercel, envie a pasta completa com index.html na raiz.
