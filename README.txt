Relatório do Projeto - Padaria do Bairro

Este relatório resume as quatro práticas já realizadas no desenvolvimento do site da Padaria do Bairro.
O projeto tem como objetivo criar uma página web completa e funcional utilizando HTML5, CSS e JavaScript.

PRÁTICA 4 - Estilização com CSS
---------------------------------------------------
Objetivo: Definir identidade visual e melhorar experiência do usuário.
Implementações realizadas:
- Criação de style.css vinculado a todas as páginas.
- Paleta de cores definida (tons terrosos, dourados ou avermelhados).
- Hierarquia tipográfica clara (h1 > h2 > h3 > p).
- Layout centralizado com container e espaçamento consistente.
- Estilização de tabelas, formulários, botões e rodapé.
- Aplicação de efeitos visuais: hover, transições suaves, foco em inputs.
- Organização do CSS com comentários e boas práticas.
- Site com identidade visual consistente, mais atrativo e responsivo.

📄 Código CSS:


body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  background-color: #dddddd;
}

header {
  background-color: #e1c542; /* Amarelo mais suave */
  padding: 20px 20px 10px; /* reduzido */
  text-align: center;
  position: relative;
  
}

header img {
  margin-top: 0;
  margin-bottom: 10px;
}
  

header h1 {
  margin-top: 0;
  font-size: 2.5rem;
  color: #000;
}



.btn-adicionar { /* Botão de adicionar */
  background-color: #ecc84f;
  border: none;
  padding: 8px 14px;
  border-radius: 5px;
  color: white;
  font-weight: bold;
  cursor: pointer;
  transition: 0.3s;
}

.btn-adicionar:hover {
  background-color: #d4ae3f;
  transform: scale(1.05); /* efeito leve de zoom */



CONCLUSÃO
---------------------------------------------------
Até o momento, o projeto evoluiu de uma simples estrutura HTML para um site funcional e estilizado, 
com navegação estruturada, formulários interativos, tabelas, imagens, vídeos e design coerente.
As quatro práticas foram concluídas com sucesso, e cada prática adicionou novos elementos técnicos: 
- Estrutura semântica (HTML)
- Conteúdo visual (imagens, vídeos, tabelas)
- Funcionalidades interativas (formulários)
- Identidade visual (CSS)
preparando terreno para etapas futuras (ex: responsividade avançada, integração com backend).

ESTRUTURA FINAL DO PROJETO (até a prática 4)
---------------------------------------------------
padaria-do-bairro/
├── index.html
├── contato.html
├── pedidos.html
├── feedback.html
├── cadastro.html
├── sobrenos.html
├── css/
│   ├── style.css
├── images/
│   ├── produtos/
│   ├── ambiente/
│   └── logo/
├── videos/
└── README.txt


Desenvolvido por Elisangela Felix

✅Link com o Resultado do site:
https://elisangelafelix.github.io/Padaria-do-Bairro-Pratica-4/
