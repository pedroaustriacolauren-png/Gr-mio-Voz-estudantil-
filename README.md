# Gr-mio-Voz-estudantil-
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Voz Estudantil | CEM Setor Leste</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}
body{
background:#f5f9ff;
color:#222;
}
header{
background:#0d47a1;
color:white;
padding:20px 8%;
display:flex;
justify-content:space-between;
align-items:center;
}
.logo{
font-size:1.8rem;
font-weight:700;
}
nav a{
color:white;
text-decoration:none;
margin-left:20px;
font-weight:500;
}
.hero{
background:linear-gradient(135deg,#0d47a1,#1976d2);
color:white;
text-align:center;
padding:100px 20px;
}
.hero h1{
font-size:3rem;
margin-bottom:15px;
}
.hero p{
font-size:1.2rem;
max-width:700px;
margin:auto;
}
.btn{
display:inline-block;
margin-top:25px;
padding:12px 25px;
background:white;
color:#0d47a1;
border-radius:30px;
font-weight:600;
text-decoration:none;
}
section{
padding:70px 8%;
}
.section-title{
font-size:2rem;
color:#0d47a1;
margin-bottom:25px;
}
.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}
.card{
background:white;
padding:25px;
border-radius:15px;
box-shadow:0 4px 12px rgba(0,0,0,0.08);
}
.card h3{
color:#0d47a1;
margin-bottom:10px;
}
.projetos{
background:white;
}
footer{
background:#0d47a1;
color:white;
text-align:center;
padding:30px;
}
form{
display:flex;
flex-direction:column;
gap:12px;
}
input, textarea{
padding:12px;
border:1px solid #ccc;
border-radius:8px;
}
button{
padding:12px;
background:#0d47a1;
color:white;
border:none;
border-radius:8px;
cursor:pointer;
}
@media(max-width:768px){
.hero h1{
font-size:2.2rem;
}
}
</style>
</head>
<body>
<header>
<div class="logo">🎓 Voz Estudantil</div>
<nav>
<a href="#sobre">Sobre</a>
<a href="#projetos">Projetos</a>
<a href="#eventos">Eventos</a>
<a href="#ouvidoria">Ouvidoria</a>
</nav>
</header>
<section class="hero">
<h1>Sua Voz Constrói a Escola</h1>
<p>
O Grêmio Estudantil Voz Estudantil representa os alunos do CEM Setor Leste,
fortalecendo a participação estudantil e construindo uma escola melhor para todos.
</p>

Conheça nossos projetos

</section>
<section id="sobre">
<h2 class="section-title">Quem Somos</h2>
<p>
A Voz Estudantil é uma organização formada por estudantes comprometidos com a democracia,
a participação e a defesa dos direitos estudantis dentro do CEM Setor Leste.
</p>
</section>
<section id="projetos" class="projetos">
<h2 class="section-title">Projetos</h2>
<div class="cards">
<div class="card">
<h3>🏫 Escola Melhor</h3>
<p>Propostas para infraestrutura e melhoria dos espaços escolares.</p>
</div>
<div class="card">
<h3>📚 Voz Acadêmica</h3>
<p>Monitorias, grupos de estudo e incentivo ao aprendizado.</p>
</div>
<div class="card">
<h3>🎭 Cultura em Movimento</h3>
<p>Eventos culturais, festivais e apresentações artísticas.</p>
</div>
<div class="card">
<h3>⚽ Esporte para Todos</h3>
<p>Competições esportivas e atividades de integração.</p>
</div>
</div>
</section>
<section id="eventos">
<h2 class="section-title">Próximos Eventos</h2>
<div class="cards">
<div class="card">
<h3>Assembleia Estudantil</h3>
<p>Discussão de pautas e sugestões dos estudantes.</p>
</div>
<div class="card">
<h3>Semana Cultural</h3>
<p>Atividades artísticas e apresentações.</p>
</div>
<div class="card">
<h3>Interclasse</h3>
<p>Competições esportivas entre as turmas.</p>
</div>
</div>
</section>
<section id="ouvidoria">
<h2 class="section-title">Ouvidoria Estudantil</h2>
<form>
<input type="text" placeholder="Seu nome">
<input type="text" placeholder="Turma">
<textarea rows="5" placeholder="Digite sua sugestão"></textarea>
<button type="submit">Enviar</button>
</form>
</section>
<footer>
<p>Grêmio Estudantil Voz Estudantil • CEM Setor Leste</p>
<p>Democracia • Participação • Representação</p>
</footer>
</body>
</html>