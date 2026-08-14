## 05. Comunicação entre os Componentes e Barramentos

Depois que os principais componentes foram inicializados, o computador precisa permitir que eles troquem dados e sinais entre si. O processador, a memória RAM, o armazenamento, a placa de vídeo e os dispositivos de entrada e saída não funcionam de forma isolada.

Essa comunicação acontece por meio de *barramentos, interfaces e controladores*, que funcionam como caminhos de comunicação entre os componentes do sistema.

Entre os principais exemplos estão:

* *PCI Express (PCIe):* utilizado por placas de vídeo, SSDs NVMe e outros dispositivos de alta velocidade;
* *USB:* utilizado por teclado, mouse, pendrives e diversos periféricos;
* *SATA:* utilizado em muitos HDs e SSDs;
* *Subsistema de memória:* responsável pela comunicação entre a CPU e a memória RAM.

De forma simplificada, podemos representar essa comunicação assim:

*CPU ↔️ RAM*

*CPU ↔️ PCIe ↔️ GPU / SSD NVMe*

*CPU ↔️ Controladores ↔️ USB / SATA / outros dispositivos*

Os barramentos transportam diferentes tipos de informações, como dados, endereços e sinais de controle. Isso permite que o processador solicite informações da memória, acesse dados armazenados em um SSD ou se comunique com dispositivos conectados ao computador.

Os *controladores* também têm um papel importante, pois ajudam a organizar a comunicação entre a CPU e diferentes tipos de hardware.

Durante a inicialização, essa comunicação é essencial para que a BIOS/UEFI consiga identificar dispositivos, acessar o armazenamento e encontrar uma opção válida de inicialização.

Depois que os componentes estão preparados e se comunicando corretamente, o próximo passo é localizar o sistema operacional e iniciar seu carregamento.
