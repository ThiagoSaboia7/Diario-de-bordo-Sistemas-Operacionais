## 04. POST e Preparação do Hardware

Depois que a BIOS/UEFI começa a executar suas rotinas de inicialização, o computador realiza uma série de verificações para confirmar se os principais componentes de hardware estão disponíveis e em condições de continuar o processo de boot.

Essa etapa é conhecida como *POST, sigla para *Power-On Self-Test.

Durante o POST, o sistema verifica e inicializa componentes essenciais, como:

* processador;
* memória RAM;
* sistema de vídeo;
* dispositivos de armazenamento;
* controladores da placa-mãe;
* dispositivos básicos de entrada e saída.

O objetivo não é realizar um teste completo de todos os componentes, mas identificar falhas importantes que poderiam impedir a continuidade da inicialização.

Caso algum problema seja encontrado, a placa-mãe pode apresentar sinais de diagnóstico, como:

* mensagens na tela;
* códigos sonoros;
* LEDs de diagnóstico;
* códigos exibidos em displays da própria placa-mãe.

Por exemplo, uma falha na memória RAM pode impedir o computador de avançar para as próximas etapas, enquanto determinados problemas de vídeo podem fazer com que a máquina ligue sem apresentar imagem no monitor.

O fluxo dessa etapa pode ser representado assim:

*BIOS/UEFI → POST → Verificação dos componentes → Hardware preparado para continuar*

O processador continua tendo um papel central nesse processo, pois é ele quem executa as instruções do firmware responsáveis por realizar essas verificações e inicializações.

Depois que os componentes essenciais estão preparados, o computador precisa permitir que eles troquem informações entre si. Para isso, entram em cena os barramentos, controladores e interfaces de comunicação.

Esse será o próximo ponto do estudo.
