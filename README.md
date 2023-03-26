RELATÓRIO - CRIAÇÃO DO SITE COFFEE SHOPS TIA ROSA

Neste projeto, foi desenvolvido um site em HTML5 e CSS, utilizando as cores do Brasil, para a COFFEE SHOPS TIA ROSA. A seguir, serão apresentados os passos para a criação do site, com imagens, textos explicativos e códigos.

Planejamento e Definição de Objetivos
O primeiro passo foi definir os objetivos específicos do projeto, que foram:

Colocar em prática o que foi estudado na disciplina;
Desenvolver um site com layout intuitivo;
Realizar a hospedagem do site;
Não desenvolver conteúdos impróprios.
Estruturação do Site
A estruturação do site foi definida a partir do modelo de site da Starbucks, com algumas adaptações. Foram criadas as seguintes seções:

Página Inicial;
Sobre Nós;
Produtos;
Lojas;
Contato.
Desenvolvimento da Página Inicial
Para a criação da página inicial, foi utilizada uma imagem de fundo em alta resolução, com a marca da COFFEE SHOPS TIA ROSA sobreposta em destaque. Também foi criado um menu de navegação no topo da página, com as seções do site.

Segue o código HTML da página inicial:

<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>COFFEE SHOPS TIA ROSA</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="#">Página Inicial</a></li>
        <li><a href="#">Sobre Nós</a></li>
        <li><a href="#">Produtos</a></li>
        <li><a href="#">Lojas</a></li>
        <li><a href="#">Contato</a></li>
      </ul>
    </nav>
  </header>
  <main>
    <div class="bg-image">
      <div class="overlay">
        <h1>COFFEE SHOPS TIA ROSA</h1>
      </div>
    </div>
  </main>
</body>
</html>

O código CSS da página inicial foi utilizado para aplicar a imagem de fundo e ajustar o menu de navegação:

.bg-image {
  background-image: url("https://i.imgur.com/CxM8jUV.jpg");
  height: 100%;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
}

.overlay {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  background-color: rgba(0, 0, 0, 0.5);
  color: white;
  width: 80%;
  padding: 60px;
}

nav {
  background-color: #002776;
  height: 50px;
  display: flex;
  justify-content: center;
}

nav ul {
  margin: 0;
  padding: 0;
  display: flex;
}

nav li {
  list-style: none;
}

nav a {
  display: block;
  padding: 0


