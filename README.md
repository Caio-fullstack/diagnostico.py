Ferramenta de Diagnóstico de Sistema em Python

Este é um script em Python que exibe informações em tempo real sobre o sistema, incluindo uso de CPU, memória RAM, disco, informações de rede e detalhes de hardware como modelo do processador e tipo de memória.

Funcionalidades?

-   Exibição colorida para fácil leitura.
-   Atualização automática das informações.
-   Coleta de dados de SO, CPU, RAM, Disco e Rede.
-   Detecção do modelo da CPU.
-   Detecção do tipo de memória RAM (DDR) em sistemas Windows.

Bibliotecas Necessárias?

Este script utiliza as seguintes bibliotecas externas:

-   `psutil`
-   `colorama`
-   `py-cpuinfo`
-   `comtypes` (apenas para Windows)

Como Executar?

1.  Clone este repositório.
2.  Instale as dependências:
    ```bash
    pip install psutil colorama py-cpuinfo comtypes
    ```
3.  Execute o script a partir de um terminal (recomenda-se executar como administrador no Windows para obter todas as informações) ou no proprio Visual Studio Code:
    ```bash
    python diagnostico.py
    ```
