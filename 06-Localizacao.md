## 06. Localização e Carregamento do Sistema Operacional

Depois que o hardware essencial foi inicializado e os dispositivos de armazenamento foram reconhecidos, a BIOS/UEFI precisa encontrar uma opção válida de inicialização para continuar o processo.

Essa etapa é conhecida como *boot*.

A BIOS/UEFI consulta as configurações de inicialização definidas no computador, normalmente organizadas em uma ordem de prioridade. Essa ordem determina quais dispositivos ou opções serão verificados primeiro.

Entre as possibilidades de boot estão:

* SSD ou HD;
* pendrive USB;
* unidade externa;
* inicialização pela rede;
* entradas específicas, como o Windows Boot Manager.

O fluxo pode ser representado assim:

*BIOS/UEFI → Ordem de Boot → Dispositivo ou opção válida → Bootloader*

Quando uma opção válida é encontrada, a BIOS/UEFI transfere a execução para um software responsável por continuar a inicialização do sistema operacional.

Esse software é chamado de *Bootloader*, ou carregador de inicialização.

O Bootloader tem a função de localizar os arquivos necessários do sistema, carregar o núcleo do sistema operacional na memória e preparar a próxima etapa da inicialização.

Exemplos de carregadores utilizados em sistemas atuais incluem:

* *Windows Boot Manager*, em sistemas Windows;
* *GRUB*, bastante utilizado em distribuições Linux.

Nesse momento, ocorre uma mudança importante no processo. Até então, o processador estava executando principalmente código relacionado ao firmware da placa-mãe. A partir do carregamento do Bootloader e, posteriormente, do Kernel, o controle começa a ser transferido para o sistema operacional.

O próximo ponto trata justamente dessa transição.
