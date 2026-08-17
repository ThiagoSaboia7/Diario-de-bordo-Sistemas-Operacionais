## 10. Fluxograma Geral do Processo

Após analisar cada etapa separadamente, é possível reunir todo o processo em um único fluxo, mostrando como o computador passa da energização inicial até o funcionamento completo sob o controle do sistema operacional.

O processo pode ser representado da seguinte forma:

*Botão Power*
↓
*Fonte de Alimentação*
↓
*Placa-mãe*
↓
*Processador inicia*
↓
*CPU executa BIOS/UEFI*
↓
*POST e preparação do hardware*
↓
*CPU, RAM, GPU, armazenamento e controladores são inicializados*
↓
*Barramentos e interfaces permitem a comunicação entre os componentes*
↓
*BIOS/UEFI consulta as opções de boot*
↓
*Sistema operacional é localizado*
↓
*Bootloader é executado*
↓
*Kernel é carregado na memória RAM*
↓
*Sistema Operacional assume o controle*
↓
*Drivers são carregados*
↓
*CPU, memória, processos e dispositivos passam a ser gerenciados pelo SO*
↓
*Dispositivos de Entrada e Saída passam a interagir com o sistema*
↓
*Computador pronto para uso*

Esse fluxograma permite visualizar que a inicialização acontece em uma sequência organizada de etapas. Cada fase depende da anterior para continuar.

Também é possível perceber a presença do *processador durante praticamente todo o processo*. Inicialmente, a CPU executa o firmware da BIOS/UEFI. Depois, executa o Bootloader e, posteriormente, passa a executar o Kernel e os demais programas controlados pelo sistema operacional.

Dessa forma, a CPU permanece como elemento central da execução, enquanto o controle do sistema passa progressivamente do firmware para o sistema operacional.
