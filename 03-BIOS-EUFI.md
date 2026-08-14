## 03. BIOS/UEFI e suas Funções

Após o processador começar a executar o firmware da placa-mãe, a *BIOS/UEFI* passa a coordenar as primeiras etapas da inicialização do computador. Sua função principal é preparar o hardware para que o sistema operacional possa ser localizado e carregado corretamente.

A *BIOS* (Basic Input/Output System) é o padrão tradicional utilizado durante muitos anos nos computadores. Já a *UEFI* (Unified Extensible Firmware Interface) é uma solução mais moderna, com maior capacidade de configuração, suporte a recursos atuais e um processo de inicialização mais avançado.

Durante a inicialização, a BIOS/UEFI executa várias funções importantes, entre elas:

* inicializar componentes básicos do computador;
* preparar a memória RAM para uso;
* identificar processador, memória, armazenamento e outros dispositivos;
* iniciar controladores essenciais;
* executar verificações de hardware;
* consultar as configurações de inicialização;
* localizar uma opção válida de boot;
* encaminhar o processo para o carregamento do sistema operacional.

O fluxo pode ser representado da seguinte forma:

*CPU → BIOS/UEFI → Inicialização do hardware → Verificações → Busca por dispositivo de boot*

É importante destacar que a BIOS/UEFI atua como uma ponte entre o momento em que o computador recebe energia e o momento em que o sistema operacional começa a ser carregado.

Nesta etapa, o processador continua executando as instruções presentes no firmware, enquanto os demais componentes são preparados para o funcionamento.

Entre essas tarefas está uma das etapas mais conhecidas da inicialização, chamada *POST*, responsável pelas verificações iniciais do hardware.

Esse será o próximo ponto do processo.
