# projetoIevrAds

📦 Controle de Doações — Vida RenovadaSistema web leve e responsivo para gestão e controle de estoque de doações em centros comunitários, focado em agilidade, acessibilidade e usabilidade em campo.

📋 Sobre o ProjetoO Vida Renovada é uma aplicação voltada para apoiar voluntários e gestores de instituições de assistência na organização, recebimento e distribuição de doações (como alimentos, mantimentos e itens variados). O sistema foi desenvolvido para operar diretamente no navegador, contando com uma interface intuitiva, navegação fluida em abas, validações em tempo real e controle dinâmico de estoque e prazos de validade.

✨ Principais FuncionalidadesDashboard Inicial: Resumo visual com métricas de itens cadastrados, lotes disponíveis e alertas de vencimento próximo.Registro de Movimentações: Cadastro dinâmico de entradas (Recebimentos) e saídas (Distribuições) com validação inteligente de saldo em estoque.Consulta de Estoque: Tabela interativa com busca em tempo real, visualização de lotes, unidades de medida e status de validade.Design Responsivo e Acessível: Layout otimizado para computadores, tablets e dispositivos móveis (com suporte a navegação por toque e barras de ferramentas adaptadas).Zero Dependências Externas: Construído utilizando tecnologias web nativas puras (Vanilla JavaScript, CSS moderno com variáveis e HTML semântico).

🚀 Tecnologias UtilizadasEste projeto foi construído utilizando as seguintes tecnologias:HTML5 (Estruturação semântica e acessibilidade com atributos ARIA)CSS3 (Variáveis CSS, Flexbox, Grid Layout, Design Responsivo e Media Queries)JavaScript (ES6+) (Manipulação do DOM, controle de estado reativo local e validação de formulários)⚙️ Como Executar o ProjetoComo a aplicação é desenvolvida em tecnologias web puras (Single File / Static Web App), você não precisa instalar nenhum ambiente Node.js complexo ou dependências externas para executá-la.Pré-requisitosApenas um navegador web moderno (Google Chrome, Mozilla Firefox, Microsoft Edge ou Safari).Passo a passo:Clone este repositório ou faça o download dos arquivos:Bashgit clone https://github.com/seu-usuario/controle-doacoes-vida-renovada.git
Abra a pasta do projeto.Dê um duplo clique no arquivo index.html (ou abra-o diretamente arrastando-o para a janela do seu navegador favorito).

📱 Demonstração da InterfaceTela InicialRegistro de MovimentaçãoConsulta de EstoqueResumo de métricas e alertasEntradas e saídas controladasFiltro e listagem por lotes

🛠️ Estrutura do CódigoO código está estruturado em um único arquivo modularizado para máxima portabilidade:Cabeçalho (<head>): Contém design tokens customizados em variáveis CSS (:root), estilos globais e regras de responsividade para diferentes tamanhos de tela.Corpo (<body>): Estruturado em um layout de aplicativo (app), dividindo a aplicação em barra de topo, menu lateral fixo/responsivo e seções de conteúdo dinâmicas.Lógica (<script>): Controla o roteamento das telas (SPA simples), o estado reativo do estoque e as regras de negócio para evitar retiradas superiores ao saldo disponível.

🤝 ContribuiçãoContribuições, relatos de bugs e sugestões de melhorias são sempre bem-vindos!Faça um Fork do projetoCrie uma Branch para sua Feature (git checkout -b feature/nova-funcionalidade)   Faça o commit das suas alterações (git commit -m 'Adiciona nova funcionalidade')   Faça o Push para a Branch (git push origin feature/nova-funcionalidade)   Abra um Pull Request  

📄 LicençaDistribuído sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.
