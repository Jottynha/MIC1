# MIC1 - Simulação de Computador Simples no Quartus II

Este projeto, chamado **MIC1**, foi desenvolvido no Quartus II e tem como objetivo a montagem de um computador simples, simulando seus principais componentes como a Unidade Lógica e Aritmética (ULA), banco de registradores e memória. O projeto foi projetado para entender e demonstrar o funcionamento básico de uma arquitetura de computador.

## Componentes Implementados

### 1. **ULA (Unidade Lógica e Aritmética)**
   - A ULA é responsável por executar operações aritméticas (adição, subtração, etc.) e lógicas (AND, OR, NOT, etc.).
   - No projeto MIC1, a ULA foi construída para suportar um conjunto básico de operações, permitindo interações com o banco de registradores.

### 2. **Banco de Registradores**
   - O banco de registradores armazena dados temporários usados pela ULA e outras partes do sistema.
   - No MIC1, foram implementados registradores de 32 bits que permitem operações de leitura e escrita de dados para a ULA e a memória.

### 3. **Memória**
   - A memória armazena dados e instruções que o processador utiliza.
   - O projeto inclui uma implementação básica de memória para leitura e escrita de dados, com capacidade limitada para simulação.

## Tecnologias Utilizadas

- **Quartus II:** Ferramenta de design e simulação de circuitos lógicos desenvolvida pela Intel/Altera.
- **VHDL ou Verilog:** Linguagem de descrição de hardware usada para implementar os componentes do MIC1.
- **ModelSim (opcional):** Para simulação e depuração dos componentes e interação entre a ULA, banco de registradores e memória.

## Funcionalidades do MIC1

- **Execução de Operações Aritméticas e Lógicas:** A ULA permite a execução de operações como adição, subtração, e operações lógicas como AND e OR.
- **Leitura e Escrita em Registradores:** O banco de registradores permite a transferência de dados entre a ULA e outros componentes.
- **Interação com a Memória:** O projeto permite a leitura e escrita na memória para simular o fluxo básico de um ciclo de execução de instruções.

## Como Usar

1. Clone o repositório:

    ```bash
    git clone https://github.com/Jottynha/MIC1.git
    ```

2. Abra o Quartus II e importe os arquivos do projeto.

3. Compile os módulos no Quartus II:

    - ULA
    - Banco de Registradores
    - Memória

4. Execute as simulações no ModelSim (opcional) ou utilize a ferramenta de simulação integrada do Quartus II para testar o funcionamento.

## Testes e Simulação

O projeto inclui scripts e arquivos de teste para validar o funcionamento dos componentes individualmente e em conjunto. A simulação cobre:

- Operações básicas da ULA (soma, subtração, AND, OR).
- Transferência de dados entre registradores.
- Interação entre registradores e a memória.

## Contribuições

Sinta-se à vontade para contribuir com melhorias ou adicionar novas funcionalidades ao MIC1. Para isso, faça um fork do projeto, crie um branch com suas modificações e envie um pull request.

Este projeto visa fornecer uma base sólida para o entendimento de como os componentes fundamentais de um computador interagem, ajudando no aprendizado da arquitetura de computadores.
