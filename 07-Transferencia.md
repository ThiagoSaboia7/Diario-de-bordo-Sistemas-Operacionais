## 07. Transferência de Controle para o Sistema Operacional

Depois que o Bootloader localiza os arquivos necessários do sistema operacional, ele carrega o *Kernel* na memória RAM e prepara o ambiente para que ele possa começar a ser executado.

O Kernel é o núcleo do sistema operacional. Ele é responsável por controlar os principais recursos do computador e servir de base para o funcionamento dos demais componentes do sistema.

A transição pode ser representada assim:

*BIOS/UEFI → Bootloader → Kernel → Sistema Operacional*

Essa etapa representa uma mudança importante no controle da máquina.

No início da inicialização, a CPU executava instruções do firmware da placa-mãe. Depois, passou a executar o código do Bootloader. Quando o Kernel é carregado e iniciado, o processador passa a executar o código do sistema operacional.

Ou seja, o hardware continua sendo o mesmo, mas muda o software responsável por coordenar o funcionamento do computador.

A partir desse momento, o Kernel passa a assumir tarefas como:

* gerenciamento do processador;
* gerenciamento da memória;
* controle de processos;
* comunicação com dispositivos;
* gerenciamento de entrada e saída;
* acesso ao armazenamento.

Essa transferência de controle é fundamental porque marca o fim da fase principal de inicialização realizada pelo firmware e o início do funcionamento do computador sob responsabilidade do sistema operacional.

Depois que o Kernel assume o controle, entram em cena os *drivers* e os mecanismos de gerenciamento de recursos, responsáveis por permitir que o sistema utilize corretamente os diferentes componentes de hardware.
