<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Casa do Santiago</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet" />
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body { font-family: 'Roboto', sans-serif; background-color: #f2f4f8; color: #333; }
    header {
      background: linear-gradient(135deg, #003366, #001f3f);
      color: white;
      padding: 50px 20px;
      text-align: center;
      animation: fadeIn 1.5s ease-in-out;
    }
    header h1 { font-size: 48px; margin-bottom: 10px; }
    header p { font-size: 18px; opacity: 0.9; }
    nav {
      background-color: #001f3f;
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 15px;
      position: sticky;
      top: 0;
      z-index: 100;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: 700;
      font-size: 16px;
      transition: 0.3s;
    }
    nav a:hover {
      text-decoration: underline;
      color: #ffd700;
    }
    section {
      max-width: 1200px;
      margin: 40px auto;
      padding: 40px;
      background: white;
      border-radius: 12px;
      box-shadow: 0 10px 20px rgba(0,0,0,0.1);
      animation: slideUp 1.2s ease;
    }
    h2 {
      font-size: 28px;
      margin-bottom: 20px;
      color: #002c5f;
      border-bottom: 2px solid #ccc;
      padding-bottom: 5px;
    }
    .article { margin-bottom: 18px; }
    .motivacao {
      background: #e6f2ff;
      padding: 20px;
      border-left: 6px solid #002c5f;
      border-radius: 8px;
      font-style: italic;
      margin-top: 30px;
    }
    .button {
      display: inline-block;
      margin-top: 20px;
      background: #002c5f;
      color: white;
      padding: 12px 30px;
      border: none;
      border-radius: 8px;
      font-size: 16px;
      cursor: pointer;
      text-decoration: none;
      transition: background 0.3s ease;
    }
    .button:hover {
      background: #001f3f;
    }
    footer {
      text-align: center;
      padding: 30px;
      background: #001f3f;
      color: white;
      margin-top: 50px;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(-20px); }
      to { opacity: 1; transform: translateY(0); }
    }
    @keyframes slideUp {
      from { opacity: 0; transform: translateY(40px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <header>
    <h1>Casa do Santiago</h1>
    <p>"Onde há ordem, há paz. Onde há flexões, houve erro."</p>
  </header>

  <nav>
    <a href="#codigo">Código Penal</a>
    <a href="#partido">Conhece o Partido</a>
    <a href="#assinatura">Assinar Compromisso</a>
    <a href="#avisos">Avisos Oficiais</a>
  </nav>

  <section id="codigo">
    <h2>Código Penal – Casa do Santiago</h2>
    <p>Consulta aqui os 35 artigos obrigatórios para todos os que entram nesta residência:</p>
    <div class="article"><strong>Artigo 1.º:</strong> Dizer "Boa tarde" à tia – <em>Punição:</em> 2 carrolos.</div>
    <div class="article"><strong>Artigo 2.º:</strong> Limpar os pés antes de entrar – <em>Punição:</em> 10 flexões.</div>
    <div class="article"><strong>Artigo 3.º:</strong> Não comer a comida do Santiago – <em>Punição:</em> 20 flexões.</div>
    <p>...e mais até ao Artigo 35.º</p>
    <a class="button" href="#">Descarregar Código PDF</a>

    <div class="motivacao">
      Este código representa o contrato sagrado da boa convivência. Quem o ignora, ignora também a honra da Casa do Santiago. Seguir as regras é símbolo de respeito e responsabilidade.
    </div>
  </section>

  <section id="partido">
    <h2>P.D.C.S. – Partido Pela Defesa da Casa do Santiago</h2>
    <p>Fundado com o objetivo de proteger a ordem interna da Casa, o P.D.C.S. é mais do que um partido: é um movimento disciplinar.</p>
    <ul>
      <li><strong>Fundador:</strong> Santiago</li>
      <li><strong>Lema:</strong> "Flexão hoje, respeito amanhã."</li>
      <li><strong>Missão:</strong> Proteger os valores, a estrutura e o espírito da residência</li>
    </ul>
    <div class="motivacao">
      O P.D.C.S. está aberto a todos os que acreditam numa casa limpa, justa e organizada. Acreditamos que através da ordem se conquista a paz, e através da paz se vive melhor. Ser do partido é ser agente da justiça e da arrumação.
    </div>
    <a class="button" href="#">Ver Manifesto do Partido</a>
  </section>

  <section id="assinatura">
    <h2>Assinatura de Compromisso</h2>
    <p>Ao assinar, confirmas a aceitação voluntária de todas as normas do Código Penal da Casa do Santiago. Com isso, assumes responsabilidade pessoal pela ordem e paz no espaço.</p>
    <p>Esta assinatura é simbólica, mas representa honra e respeito perante os restantes moradores e visitantes.</p>
    <a class="button" href="#">Assinar Agora</a>
  </section>

  <section id="avisos">
    <h2>Avisos Oficiais</h2>
    <p><strong>📢 ATENÇÃO:</strong> Novas diretrizes foram impostas para acesso à Casa do Santiago. O cumprimento total do Código é obrigatório para entrada e permanência.</p>
    <p>Não são permitidas exceções, nem desculpas. Cada artigo foi desenhado para garantir o bem-estar de todos.</p>
    <div class="motivacao">
      O respeito é a base da confiança. Confiança gera tranquilidade. E tranquilidade é o que esta casa oferece a quem segue as regras.
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Casa do Santiago – Partido P.D.C.S. | Todos os direitos reservados.</p>
  </footer>
</body>
</html>

