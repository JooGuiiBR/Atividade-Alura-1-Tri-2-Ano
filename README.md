<!DOCTYPE html>
<html lang="pt-br">

<head>
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
   <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
   <link rel="stylesheet" href="style.css">
   <title>Meu portfólio</title>
</head>

<body>
   <header class="container text-center">
      <img src="img/Portfloio.jpeg" alt="avatar do João" class="rounded-circle" width="150" height="150">
      <p class="lead">Eu sou João</p>
      <h1>Eu estou aprendendo Programação</h1>
      <p>Sou aluno do Colégio Dona Branca do Nascimento Miranda e estou aprendendo a criar sites com a professora Fernanda!</p>
      <p>Minhas habilidades</p>
      <div>
         <p class="badge bg-secondary">HTML</p>
         <p class="badge bg-secondary">CSS</p>
         <p class="badge bg-secondary">JavaScript</p>
         <p class="badge bg-secondary">Scratch</p>
      </div>
   </header>

   <main class="container mt-5">
      <h2>Meus projetos</h2>
      <div class="row">
         <!-- Projeto 1 -->
         <div class="col-md-4">
            <div class="card">
               <img src="img/projeto-joao1.png" class="card-img-top" alt="Imagem do projeto de site pessoal">
               <div class="card-body">
                  <h5 class="card-title">Meu Primeiro Site</h5>
                  <p class="card-text">Criei meu primeiro site usando HTML e CSS. Ele mostra quem eu sou, onde estudo e o que estou aprendendo na aula de programação.</p>
                  <button type="button" class="btn btn-link" data-bs-toggle="modal" data-bs-target="#modal1">Veja o projeto</button>
               </div>
            </div>
         </div>

         <!-- Projeto 2 -->
         <div class="col-md-4">
            <div class="card">
               <img src="img/projeto-joao2.png" class="card-img-top" alt="Imagem do projeto de perguntas interativas">
               <div class="card-body">
                  <h5 class="card-title">Quiz Interativo</h5>
                  <p class="card-text">Um quiz divertido feito com JavaScript onde as pessoas testam seus conhecimentos sobre tecnologia e programação básica.</p>
                  <button type="button" class="btn btn-link" data-bs-toggle="modal" data-bs-target="#modal2">Veja o projeto</button>
               </div>
            </div>
         </div>

         <!-- Projeto 3 -->
         <div class="col-md-4">
            <div class="card">
               <img src="img/projeto-joao3.png" class="card-img-top" alt="Imagem do jogo no Scratch">
               <div class="card-body">
                  <h5 class="card-title">Jogo de Corrida com Scratch</h5>
                  <p class="card-text">Criei um jogo simples no Scratch onde um carrinho precisa desviar de obstáculos para ganhar pontos. Foi muito legal programar isso!</p>
                  <button type="button" class="btn btn-link" data-bs-toggle="modal" data-bs-target="#modal3">Veja o projeto</button>
               </div>
            </div>
         </div>
      </div>
   </main>

   <!-- Modal 1 -->
   <div class="modal" id="modal1" tabindex="-1">
      <div class="modal-dialog">
         <div class="modal-content">
            <div class="modal-header">
               <h5 class="modal-title">Meu Primeiro Site</h5>
               <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
            </div>
            <div class="modal-body">
               <p>Este foi o primeiro site que fiz na aula de Programação. Usei HTML para criar a estrutura e CSS para deixar tudo colorido e bonito.</p>
               <p>O site tem uma apresentação sobre mim e os meus objetivos como estudante da área de tecnologia.</p>
               <img src="img/projeto-joao1.png" class="img-fluid w-100" alt="Imagem do site do João">
            </div>
         </div>
      </div>
   </div>

   <!-- Modal 2 -->
   <div class="modal" id="modal2" tabindex="-1">
      <div class="modal-dialog">
         <div class="modal-content">
            <div class="modal-header">
               <h5 class="modal-title">Quiz Interativo</h5>
               <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
            </div>
            <div class="modal-body">
               <p>Um quiz que fiz com perguntas sobre HTML, CSS e lógica de programação. O usuário recebe uma pontuação ao final do quiz.</p>
               <img src="img/projeto-joao2.png" class="img-fluid w-100" alt="Imagem do quiz interativo do João">
            </div>
         </div>
      </div>
   </div>

   <!-- Modal 3 -->
   <div class="modal" id="modal3" tabindex="-1">
      <div class="modal-dialog">
         <div class="modal-content">
            <div class="modal-header">
               <h5 class="modal-title">Jogo de Corrida com Scratch</h5>
               <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
            </div>
            <div class="modal-body">
               <p>Com o Scratch, desenvolvi um jogo de corrida simples com pontuação. Usei blocos de código para movimentar o carro e gerar obstáculos.</p>
               <img src="img/projeto-joao3.png" class="img-fluid w-100" alt="Imagem do jogo do João no Scratch">
            </div>
         </div>
      </div>
   </div>

   <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html>
