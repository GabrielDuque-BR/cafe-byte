☕ Café Byte

Uma experiência digital para quem ama café e tecnologia.

"🌐 Acessar demonstração" (https://gabrielduque-br.github.io/cafe-byte/) · "💻 Ver código-fonte" (https://github.com/GabrielDuque-BR/cafe-byte)

---

📖 Sobre o projeto

O Café Byte é uma aplicação web front-end que simula a experiência digital de uma cafeteria, oferecendo um cardápio interativo, gerenciamento de pedidos, consulta de endereço e integração com dados meteorológicos.

Desenvolvido como projeto educacional durante o curso Web do Zero, o site reúne conceitos fundamentais de desenvolvimento web em uma aplicação prática, responsiva e interativa.

O projeto foi construído com tecnologias nativas da web, sem a utilização de frameworks, permitindo compreender diretamente o funcionamento do HTML, CSS e JavaScript.

✨ Funcionalidades

Funcionalidade| Descrição
☕ Cardápio dinâmico| Produtos apresentados automaticamente por JavaScript
🔍 Busca de produtos| Pesquisa por nome em tempo real
🏷️ Filtros| Organização por bebidas, doces e salgados
🛒 Carrinho| Adição e remoção de produtos e cálculo de valores
💾 Persistência local| Armazenamento do pedido com "localStorage"
📍 Consulta de CEP| Preenchimento automático de endereço via ViaCEP
🌡️ Temperatura atual| Integração com a API Open-Meteo
🌙 Modo escuro| Alternância entre temas claro e escuro
🕒 Horário de funcionamento| Indicação dinâmica de aberto ou fechado
👋 Saudação personalizada| Mensagem de acordo com o horário do visitante
📱 Design responsivo| Interface adaptável a diferentes dispositivos
🗺️ Mapa integrado| Visualização de localização com OpenStreetMap

🖥️ Interface e experiência do usuário

O projeto foi desenvolvido priorizando uma navegação simples e uma identidade visual inspirada no universo das cafeterias.

Principais decisões de interface:

- Paleta de cores em tons de café, creme e laranja.
- Tipografia Poppins para legibilidade e consistência visual.
- Cards de produtos com organização em CSS Grid.
- Layout responsivo com Flexbox e media queries.
- Feedback visual para ações do usuário.
- Menu adaptado para dispositivos móveis.
- Estados visuais para filtros, botões e status de funcionamento.
- Indicadores de foco para navegação por teclado.

🧰 Tecnologias e ferramentas

Tecnologia| Aplicação
HTML5| Estrutura semântica e formulários
CSS3| Estilização, responsividade e animações
JavaScript| Lógica de interface e interatividade
DOM API| Manipulação dinâmica dos elementos
Fetch API| Requisições HTTP assíncronas
Local Storage| Persistência de dados no navegador
GitHub| Versionamento e hospedagem do código
GitHub Pages| Publicação da aplicação estática

Integrações externas

Open-Meteo

API utilizada para consultar a temperatura atual e apresentar sugestões de bebidas de acordo com as condições climáticas.

Documentação: https://open-meteo.com/

ViaCEP

Serviço utilizado para consultar informações de endereço a partir de um CEP brasileiro.

Documentação: https://viacep.com.br/

OpenStreetMap

Plataforma utilizada para incorporar a visualização de um mapa à página.

Site: https://www.openstreetmap.org/

🏗️ Arquitetura e funcionamento

O Café Byte utiliza uma arquitetura client-side, na qual a interface e as funcionalidades são executadas diretamente no navegador.

O JavaScript é responsável por renderizar o cardápio, controlar o carrinho, processar interações, armazenar dados locais e consumir serviços externos.

Fluxo simplificado:

1. O navegador carrega a estrutura HTML e os estilos CSS.
2. O JavaScript inicializa a interface e apresenta os produtos.
3. O visitante pesquisa, filtra e adiciona produtos ao carrinho.
4. Os itens selecionados são armazenados localmente no navegador.
5. As APIs externas fornecem informações de clima e endereço.
6. O formulário apresenta uma confirmação simulada do pedido.

Importante: o projeto não possui backend próprio, banco de dados ou processamento real de pagamentos e pedidos. A finalização é demonstrativa, e os dados do carrinho são armazenados apenas no navegador do visitante.

📁 Estrutura do projeto

O projeto está publicado a partir do arquivo principal:

cafe-byte/
├── index.html
└── README.md

Na versão analisada, o "index.html" contém a estrutura da página e também blocos de CSS e JavaScript incorporados. O código faz referência a arquivos externos "style.css" e "script.js", que podem ser utilizados em uma futura reorganização do projeto.

🚀 Executando localmente

Pré-requisitos

- Navegador moderno, como Chrome, Firefox ou Edge.
- Conexão com a internet para carregar fontes e consultar APIs externas.

Instalação

Clone o repositório:

git clone https://github.com/GabrielDuque-BR/cafe-byte.git

Acesse a pasta:

cd cafe-byte

Abra o arquivo "index.html" no navegador.

Não é necessário instalar dependências, frameworks ou servidores de aplicação para visualizar a interface.

📚 Conceitos aplicados

O desenvolvimento deste projeto envolveu:

- Estruturação semântica com HTML.
- Estilização com seletores, classes e variáveis CSS.
- Layouts com Flexbox e CSS Grid.
- Responsividade e media queries.
- Funções, condicionais, arrays e objetos em JavaScript.
- Manipulação e atualização do DOM.
- Eventos de clique, digitação e envio de formulários.
- Operações com "localStorage".
- Programação assíncrona com "async/await".
- Consumo e tratamento básico de respostas de APIs.
- Publicação de páginas estáticas com GitHub Pages.

🔮 Possíveis evoluções

O Café Byte também serve como base para a implementação de novos recursos:

- [ ] Separar HTML, CSS e JavaScript em arquivos independentes.
- [ ] Implementar validações adicionais nos formulários.
- [ ] Melhorar a acessibilidade dos componentes interativos.
- [ ] Adicionar testes automatizados.
- [ ] Desenvolver um backend para registrar pedidos.
- [ ] Integrar um banco de dados.
- [ ] Criar um painel administrativo para gerenciamento do cardápio.
- [ ] Implementar autenticação e acompanhamento de pedidos.

Esses recursos são possibilidades de desenvolvimento futuro e não fazem parte da implementação atual.

👨‍💻 Autor

Gabriel Tobias Ramos Duque

Estudante de Análise e Desenvolvimento de Sistemas, em formação na área de desenvolvimento de software.

Este projeto faz parte da minha trajetória de aprendizado prático em programação e da construção do meu portfólio profissional.

GitHub: "@GabrielDuque-BR" (https://github.com/GabrielDuque-BR)

---

Café Byte — 2026

Projeto educacional desenvolvido durante o curso Web do Zero.

Feito com ☕, curiosidade e muitas linhas de código.
