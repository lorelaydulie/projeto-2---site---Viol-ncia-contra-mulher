<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portal de Apoio ao Estudante | Acolhimento e Empatia</title>
  <link rel="stylesheet" href="style.css" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
</head>
<body>

  <div class="acessibilidade-bar">
    <span><i class="fa-solid fa-universal-access"></i> Acessibilidade:</span>
    <button id="btn-fonte-aumentar" title="Aumentar Fonte">A+</button>
    <button id="btn-fonte-diminuir" title="Diminuir Fonte">A-</button>
    <button id="btn-alto-contraste" title="Alternar Alto Contraste"><i class="fa-solid fa-circle-half-stroke"></i> Alto Contraste</button>
  </div>

  <header>
    <div class="logo">
      <h1><i class="fa-solid fa-heart-pulse"></i> Acolhimento</h1>
    </div>
    <nav>
      <ul>
        <li><a href="#inicio" class="nav-link active">Início</a></li>
        <li><a href="#escuta" class="nav-link">Portal de Escuta</a></li>
        <li><a href="#quiz" class="nav-link">Quiz</a></li>
        <li><a href="#referencias" class="nav-link">Referências</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="inicio" class="hero">
      <h2>Portal de Apoio ao Estudante</h2>
      <p class="boas-vindas">
        Bem-vindo ao Portal de Apoio ao Estudante. Aqui você encontrará informações, orientações e apoio sobre situações vivenciadas no ambiente escolar, incentivando a empatia, o respeito e o combate ao preconceito e à violência.
      </p>
      
      <div class="banner-imagem">
        <img src="https://images.unsplash.com/photo-1529156069898-49953e39b3ac?auto=format&fit=crop&w=1000&q=80" alt="Estudantes unidos demonstrando apoio e amizade" />
      </div>

      <div class="card-destaque">
        <blockquote class="frase-motivacional">
          <i class="fa-solid fa-quote-left"></i> "Um espaço seguro para compartilhar histórias, encontrar apoio e saber que você nunca está sozinho."
        </blockquote>
        <a href="#escuta" class="btn-acao">Acessar Portal de Escuta</a>
      </div>
    </section>

    <section id="escuta" class="container-escuta secao-espaco">
      <h3><i class="fa-solid fa-comments"></i> Portal de Escuta</h3>
      <p class="boas-vindas">Precisa desabafar? Escreva no formulário abaixo. Lembre-se: esta é uma simulação segura e nenhuma informação será gravada.</p>
      
      <div class="alerta-simulacao">
        <i class="fa-solid fa-shield-halved"></i> <strong>Espaço Seguro:</strong> Suas palavras não serão salvas em nenhum servidor.
      </div>

      <form id="form-escuta">
        <label for="nome">Nome ou Apelido (Opcional):</label>
        <input type="text" id="nome" placeholder="Como quer ser chamado(a)?" />

        <label for="mensagem">Seu Desabafo / Mensagem:</label>
        <textarea id="mensagem" rows="5" placeholder="Escreva o que está sentindo..." required></textarea>

        <button type="submit" class="btn-enviar"><i class="fa-solid fa-paper-plane"></i> Enviar Desabafo</button>
      </form>

      <div id="card-resposta" class="card-resposta hidden">
        <h4><i class="fa-solid fa-heart"></i> Mensagem de Acolhimento</h4>
        <p id="texto-resposta-acolhimento"></p>
      </div>

      <div class="orientacoes-ajuda">
        <h4><i class="fa-solid fa-hand-holding-heart"></i> Onde buscar apoio no dia a dia:</h4>
        <ul>
          <li><strong>Na Escola:</strong> Procure um professor de confiança, o pedagogo ou a direção escolar.</li>
          <li><strong>Em Casa:</strong> Converse com familiares ou adultos de sua confiança.</li>
          <li><strong>Canais Gratuitos de Apoio:</strong>
            <ul>
              <li><strong>CVV (Centro de Valorização da Vida):</strong> Ligue <strong>188</strong> (Ligação gratuita 24h) ou acesse <a href="https://www.cvv.org.br" target="_blank" rel="noopener">cvv.org.br</a>.</li>
              <li><strong>Canal Pode Falar (UNICEF):</strong> Apoio em saúde mental para jovens em <a href="https://www.podefalar.org.br" target="_blank" rel="noopener">podefalar.org.br</a>.</li>
              <li><strong>Central de Atendimento à Mulher:</strong> Ligue <strong>180</strong>.</li>
            </ul>
          </li>
        </ul>
      </div>
    </section>

    <section id="quiz" class="container-quiz secao-espaco">
      <h3><i class="fa-solid fa-circle-question"></i> Quiz Interativo: Empatia e Respeito</h3>
      <p class="boas-vindas">Teste seus conhecimentos sobre convivência escolar, segurança e respeito às diferenças!</p>

      <form id="quiz-form">
        <div class="questao">
          <p class="pergunta">1. Um colega recebe piadas e apelidos pejorativos repetidamente no grupo da turma. Essa atitude configura:</p>
          <label><input type="radio" name="p1" value="a" required> Apenas uma brincadeira inofensiva entre amigos.</label><br>
          <label><input type="radio" name="p1" value="b"> Cyberbullying, pois envolve ofensas repetidas no meio digital.</label><br>
          <label><input type="radio" name="p1" value="c"> Algo normal que todo estudante deve aceitar.</label>
        </div>

        <div class="questao">
          <p class="pergunta">2. Qual a melhor atitude ao presenciar um ato de preconceito ou bullying na escola?</p>
          <label><input type="radio" name="p2" value="a"> Rir e compartilhar a situação com outros colegas.</label><br>
          <label><input type="radio" name="p2" value="b" required> Oferecer apoio à vítima e avisar um professor ou equipe pedagógica.</label><br>
          <label><input type="radio" name="p2" value="c"> Ignorar completamente e fingir que nada aconteceu.</label>
        </div>

        <div class="questao">
          <p class="pergunta">3. Em relação à segurança digital, qual destas senhas é considerada a mais segura?</p>
          <label><input type="radio" name="p3" value="a"> 12345678</label><br>
          <label><input type="radio" name="p3" value="b"> nomedocachorro2024</label><br>
          <label><input type="radio" name="p3" value="c" required> P@ss#E5tula!92</label>
        </div>

        <div class="questao">
          <p class="pergunta">4. O que caracteriza uma atitude inclusiva na sala de aula?</p>
          <label><input type="radio" name="p4" value="a" required> Respeitar as diferenças, integrar todos nas atividades e combater discriminações.</label><br>
          <label><input type="radio" name="p4" value="b"> Formar grupos apenas com pessoas que pensam exatamente igual a você.</label><br>
          <label><input type="radio" name="p4" value="c"> Separar colegas por características físicas ou sociais.</label>
        </div>

        <div class="questao">
          <p class="pergunta">5. Se um(a) amigo(a) confidenciar que está passando por sofrimento emocional intenso, o que fazer?</p>
          <label><input type="radio" name="p5" value="a"> Guardar segredo absoluto, mesmo que haja risco à vida dele(a).</label><br>
          <label><input type="radio" name="p5" value="b" required> Ocupar-se em escutar com carinho e incentivá-lo(a) a buscar ajuda de um adulto responsável ou profissional.</label><br>
          <label><input type="radio" name="p5" value="c"> Dizer que é exagero e ignorar o sentimento.</label>
        </div>

        <button type="submit" class="btn-enviar"><i class="fa-solid fa-check"></i> Enviar Respostas</button>
      </form>

      <div id="resultado-quiz" class="card-resposta hidden">
        <h4><i class="fa-solid fa-award"></i> Resultado do Quiz</h4>
        <p id="texto-resultado"></p>
      </div>
    </section>

    <section id="referencias" class="container-referencias secao-espaco">
      <h3><i class="fa-solid fa-book-bookmark"></i> Referências e Fontes Confiáveis</h3>
      <p class="boas-vindas">Todo o conteúdo deste portal foi baseado em materiais de instituições governamentais e de saúde:</p>
      <ul>
        <li><a href="https://www.gov.br/mec/pt-br" target="_blank" rel="noopener"><i class="fa-solid fa-arrow-up-right-from-square"></i> Ministério da Educação (MEC)</a> – Cartilhas de Convivência Escolar.</li>
        <li><a href="https://www.unicef.org/brazil/" target="_blank" rel="noopener"><i class="fa-solid fa-arrow-up-right-from-square"></i> UNICEF Brasil</a> – Projetos de Proteção à Infância e Adolescência.</li>
        <li><a href="https://safernet.org.br/" target="_blank" rel="noopener"><i class="fa-solid fa-arrow-up-right-from-square"></i> SaferNet Brasil</a> – Orientação sobre Segurança Digital e Cyberbullying.</li>
        <li><a href="https://www.cvv.org.br/" target="_blank" rel="noopener"><i class="fa-solid fa-arrow-up-right-from-square"></i> Centro de Valorização da Vida (CVV)</a> – Apoio Emocional e Prevenção.</li>
      </ul>
    </section>
  </main>

  <footer>
    <p>&copy; 2026 Portal de Apoio ao Estudante | Projeto Acadêmico</p>
    <button id="btn-topo" title="Voltar ao Topo"><i class="fa-solid fa-arrow-up"></i> Voltar ao topo</button>
  </footer>

  <script src="script.js"></script>
</body>
</html>