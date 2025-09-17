Relatório do Projeto - Padaria do Bairro

Este relatório resume as quatro práticas já realizadas no desenvolvimento do site da Padaria do Bairro.
O projeto tem como objetivo criar uma página web completa e funcional utilizando HTML5, CSS e JavaScript.


Prática 1 - Estrutura HTML
---------------------------------------------------
Objetivo: Construir a primeira versão do site utilizando HTML5 semântico.
Implementações realizadas:
- Criação de página inicial (index.html) com estrutura HTML5 válida.
- Inclusão de header, main e footer.
- Definição de título principal (<h1>) com nome da padaria.
- Subdivisão em seções (<h2> e <h3>) para: Sobre Nós, Produtos, Diferenciais, Localização e Horários.
- Escrita de parágrafos descritivos para apresentar a padaria.
- Criação de listas ordenadas (horários) e não-ordenadas (produtos e diferenciais).

📄 Código:
<header> <!-- contém título principal (h1), slogan, imagem da padaria e navegação -->

    <h1>Padaria do Bairro</h1> <!-- Título principal -->

    <p>Tradição e sabor desde 1985</p> <!-- Descrição -->
    </header>
 
    <main> <!-- conteúdo principal dividido em seções semânticas -->
    <section> <!-- Seção SOBRE NÓS e etc... -->
        <h2> Sobre Nós</h2>
        <h3>Nossa Historia</h3>
        <p>A Padaria do Bairro foi fundada em 1985 com o obetivo de oferecer produos frescos e de alta qualidade para a comunidade local.</p>
        <h3>Nossa Missão</h3>
        <p>Oferecer alimentos deliciosos e saudáveis, promovendo o bem-estar e a satisfação dos nossos clientes.</p>
        <h2>Nossos Produtos</h2>
        <h3>Pães Tradicionais</h3>
        <ul> <!-- subseção com descrições -->
            <li> Pão francês tradicional </li>
            <li> Pão de açúcar integral </li>
        </ul> 


PRÁTICA 2 - Tabelas, Imagens e Vídeos
---------------------------------------------------
Objetivo: Enriquecer o site com conteúdo visual e informações estruturadas.
Implementações realizadas:
- Criação de tabela de cardápio (categoria, produto, descrição e preço).
- Criação de tabela com horários detalhados de funcionamento.
- Inserção de imagens dos produtos e fachada da padaria, com atributos alt para acessibilidade.
- Inclusão de vídeo institucional via <video> (local) ou <iframe> (YouTube).
- Organização de pastas: images/, videos/.

📄 Código:
	 <table>
            <body>
             <thead>
                <tr>
                    <th>Categoria</th>
                    <th>Produto</th>
                    <th>Descrição</th>
                    <th>Preços</th>
                </tr>
                <tr>
                    <td> Pães </td>
                    <td> Pão Francês </td>
                    <td> Crocante por fora e macio por dentro </td>
                    <td> R$ 0,80 </td>
                </tr>
 	</tbody>
	</thead>
	</table>
	
        <img src="images/produto/pao-frances.png" alt="Pão Francês" width="50px" height="50px">

 	<video controls width="560">
            <source src="videos/video-institucional.mp4" type="video/mp4">
        </video>
        <h3>Nossa Historia</h3>
        <iframe src="https://tecnicofat.github.io/files/videos/padaria.mp4" title="padaria" frameborder="0" allow="accelerometer; autoplay; clipboard write; encrypted media; gyroscope; picture in picture; web share" referrerpolicy="strict origin when cross origin" 
        allowfullscreen></iframe>


PRÁTICA 3 - Desenvolvimento de Formulários
---------------------------------------------------
Objetivo: Criar formulários para interação com clientes.
Implementações realizadas:
- Formulário de Contato (Nome, Email, Telefone, Assunto, Mensagem).
- Formulário de Pedidos Especiais (produto, sabor, data, observações).
- Formulário de Feedback (avaliação, comentários).
- Formulário de Cadastro/Newsletter (dados pessoais, endereço, preferências, termos).
- Uso de validações HTML5 (required, pattern, minlength).
- Estrutura semântica com fieldset e legend para organização.
- Navegação entre páginas: contato.html, pedidos.html, feedback.html, cadastro.html.

📄 Código:
<form >
        <fieldset>
        <legend> <h3> 📝 Contato Geral</h3> </legend>
        <label for="nome">👤Nome:</label>
        <input type="text" id="nome" name="nome" required><br> <br>

        <label for="email">📧Email:</label>
        <input type="email" id="email" name="email" required><br> <br>

        <label for="telefone">📞Telefone:</label>
        <input type="tel" id="telefone" placeholder="(XX) XXXXX-XXXX " ><br> <br>
        </fieldset>

	<button type="submit">Enviar Mensagem</button>

</form>


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