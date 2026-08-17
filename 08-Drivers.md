## 8. Drivers e Gerenciamento de Recursos

Depois que o Kernel assume o controle da máquina, o sistema operacional precisa administrar os recursos disponíveis e se comunicar corretamente com os diferentes dispositivos de hardware.

É nesse momento que entram os *drivers*.

Os drivers são softwares responsáveis por permitir a comunicação entre o sistema operacional e determinados componentes de hardware. Cada tipo de dispositivo possui características próprias, e o driver funciona como uma camada que permite ao sistema utilizar esses recursos de forma adequada.

Exemplos de drivers incluem:

* driver de vídeo;
* driver de áudio;
* driver de rede;
* driver de armazenamento;
* drivers de dispositivos USB.

De forma simplificada, essa comunicação pode ser representada assim:

*Aplicação → Sistema Operacional → Driver → Hardware*

Além dos drivers, o sistema operacional também utiliza mecanismos responsáveis pelo *gerenciamento de recursos*.

Entre os principais estão:

* *Gerenciamento da CPU:* define quais processos ou threads poderão utilizar o processador em cada momento;
* *Gerenciamento de memória:* controla como a memória RAM será distribuída entre os programas;
* *Gerenciamento de processos:* acompanha os programas em execução e organiza suas tarefas;
* *Gerenciamento de dispositivos:* coordena o acesso ao hardware e evita conflitos entre diferentes programas;
* *Gerenciamento de armazenamento:* organiza o acesso a arquivos e dados armazenados.

No caso do processador, um dos mecanismos mais importantes é o *escalonador, também chamado de *scheduler. Ele decide qual tarefa deve utilizar a CPU em determinado momento.

Isso permite que vários programas funcionem aparentemente ao mesmo tempo, mesmo quando disputam os mesmos recursos do processador.

Por exemplo:

*Navegador + Jogo + Spotify + Discord → Escalonador → CPU*

O sistema operacional alterna a execução entre diferentes tarefas e distribui o uso dos recursos de acordo com suas regras internas.

Depois que drivers e gerenciadores entram em funcionamento, o computador já consegue responder de forma organizada aos dispositivos de entrada e produzir resultados por meio dos dispositivos de saída.

Esse será o último ponto do processo.
