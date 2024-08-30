%%html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfólio Pessoal</title>
    <style>
        /* Estilo aqui */
        *{
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            text-align: center;
        }
        body{
            font-family: Serif, sans-serif;
            font-size: 16px;
            line-height: 1.6;
            color: #454242;
            background-color: #fffdd0;
            padding-top: 60px;
        }
        header{
            top: 0;
            width: 100%;
            padding: 9px;
            color: #ebdf7a;
            background-color: #fffff0;
        }
        header nav ul{
            list-style: none;
            dispaly: flex;
            justify-contente: center;
        }
        header nav ul li{
          margin: 0 20px;
        }
        header nav ul li a{
            color: #ebdf7a;
            text-decoration: none;
            font-weight: bold;
        }
        /* Estilo das seções */
        section{
          padding: 40px 20px;
          max-width: 800px;
          margin: auto;
        }
        section h1{
          margin-botton: 20px;
        }
        /* Estilo do formulario */
        form{
          display: flex;
          flex-direction: column;
        }
        form label{
          margin-botton: 5px;
          font-weight: bold;
        }
        form input, form textarea{
          margin-botton: 15px;
          padding: 10px;
          border: 1px solid #ccc;
          border-radius: 4px;
          front-size: 16px;
        }
        form button{
          padding: 10px;
          background-color: #fffff0;
          color: #ebdf7a;
          border: none;
          border-radius: 5px;
          cursor: pointer;
          font-size: 16px;
        }
        footer{
          text-align: center;
          padding: 15px;
          background-color: #fffff0;
          color: #ebdf7a;
        }
</style>
</head>
<body>
    <!-- Cabeçalho com menu de navegação -->
    <header>
        <nav>
            <ul>
                <li><a href="#sobre-mim">Sobre Mim</a></li>
                <li><a href="#formacao">Formação</a></li>
                <li><a href="#portfolio">Portfólio</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>
 <!--  "Sobre Mim" -->
    <section id="sobre-mim">
        <h1>Sobre Mim</h1>
        <p>Olá! Meu nome é Isabelly. Estou cursando Análise e Desenvolvimento de sistemas, pretendo aprofundar meus estudos em Cybersegurança no exterior.</p>
        <p>Apaixonada pela área de exatas, gosto de aprender coisas novas e sempre estar atualizada no mundo da tecnologia.</p>
    </section>
 <!-- "Formação" -->
    <section id="formacao">
        <h1>Formação</h1>
        <p>Tecnologia em Análise e Desenvolvimento de sistemas pela Uninter.</p>
        <p>Idiomas: Português (nativo), Inglês (intermediário).</p>
    </section>
  <!-- "Portfólio" -->
    <section id="portfolio">
        <h1>Portfólio</h1>
        <!-- trabalhos -->
        <ul>
            <li>Projeto 1 </li>
            <li>Projeto 2 </li>
            <li>Projeto 3 </li>
        </ul>
    </section>
  <!-- "Contato" com um formulário -->
  <section id="contato">
      <h1>Contato</h1>
      <form>
           <label for="nome">Nome:</label>
           <input type="text" id="nome" name="nome" required>
           
<label for="email">E-mail:</label>
<input type="email" id="email" name="email" required>
           
<label for="mensagem">Mensagem:</label>
<textarea id="mensagem" name="mensagem" rows="5" required></textarea>
          
<button type="submit">Enviar</button>
        </form>
</section>
<!-- Rodapé -->
    <footer>
        <p> 2024 Isabelly Thaina Silva.</p>
    </footer>
</body>
</html>
