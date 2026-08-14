## 02. Primeiras Instruções do Processador

Depois que a alimentação do computador é estabilizada e o processador sai do estado de reset, a CPU começa a executar suas primeiras instruções. Nesse momento, o sistema operacional ainda não está carregado, portanto o processador precisa iniciar a execução de um código que já esteja disponível no próprio computador.

Esse código faz parte do *firmware da placa-mãe*, normalmente identificado como BIOS ou UEFI. De forma simplificada, o processador começa a buscar e executar as instruções necessárias para iniciar a plataforma e preparar os demais componentes do computador.

O fluxo pode ser representado assim:

*CPU inicia → localiza o firmware → começa a executar BIOS/UEFI*

Essa etapa é importante porque mostra que o processador não inicia diretamente o Windows ou outro sistema operacional. Antes disso, ele precisa executar um conjunto de instruções responsáveis por preparar o hardware e dar continuidade ao processo de inicialização.

Também é importante diferenciar duas funções:

*BIOS/UEFI:* contém as rotinas e instruções necessárias para a inicialização.

*Processador:* executa essas instruções.

Portanto, mesmo quando dizemos que a BIOS/UEFI está “iniciando o computador”, quem efetivamente executa esse código é a CPU.

A partir desse ponto, o firmware passa a realizar tarefas como inicialização de memória, identificação de dispositivos e verificações de hardware, preparando a máquina para encontrar e carregar um sistema operacional.

Essa etapa leva ao próximo ponto do estudo:

*Quais funções a BIOS/UEFI executa durante a inicialização do computador?*
