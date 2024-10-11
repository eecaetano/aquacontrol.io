Caetano AquaControl
Descrição
O Caetano AquaControl é um sistema de controle de nível de água desenvolvido para monitorar e gerenciar o consumo de água em caixas d’água. Utilizando tecnologias web como HTML, CSS, JavaScript e a biblioteca p5.js, o sistema oferece uma interface interativa e visualmente atraente. O servidor é construído com Node.js, garantindo uma operação eficiente e escalável.

Funcionalidades
Monitoramento em Tempo Real: Exibe o nível de água em litros e mililitros, atualizando a cada intervalo de tempo definido.
Relógio Local: Mostra a hora local do computador, proporcionando uma experiência mais realista.
Alertas de Nível de Água: Notifica o usuário quando o nível de água atinge 50% da capacidade e quando está próximo do esgotamento.
Tabela de Registro: Registra o nível de água e o tempo em uma tabela, permitindo o acompanhamento histórico do consumo.
Controle de Consumo: Botões para interromper e reiniciar a contagem de tempo e o controle de consumo de água.
Página Inicial: Um painel de controle com links úteis para previsão do tempo, informações sobre a crise hídrica, incentivos de prevenção ao desperdício de água e dicas de economia na conta d’água.
Estrutura do Diretório
water-level-control/
├── public/
│   ├── css/
│   │   └── styles.css
│   ├── js/
│   │   ├── p5.min.js
│   │   └── sketch.js
│   ├── index.html
│   ├── control-panel.html
│   └── logo.png
├── server.js
└── package.json
