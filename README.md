# Desafio Controle de Fluxo

Este projeto é um programa que recebe dois números inteiros e realiza uma contagem incremental, imprimindo no console o valor de cada interação. Se o primeiro número for maior que o segundo, uma exceção personalizada será lançada.

### Funcionalidades
* **Entrada de parâmetros via terminal:** O programa aceita dois números inteiros como entrada.
* **Contagem incremental:** O sistema realiza uma contagem baseada na diferença entre os dois números, exibindo o valor de cada interação.
* **Exceção personalizada:** Se o primeiro número for maior que o segundo, a exceção `ParametrosInvalidosException` é lançada com a mensagem "O segundo parâmetro deve ser maior que o primeiro".

### Como Funciona
* **Entrada de parâmetros:** O usuário deve fornecer dois números inteiros via terminal. O programa então realiza a validação.
* **Validação:** Se o primeiro número for maior que o segundo, o sistema lança a exceção customizada `ParametrosInvalidosException`.
* **Contagem:** Se os parâmetros forem válidos, o sistema executa um loop que imprime os números incrementados até atingir a diferença entre os dois números.

### Tecnologias Utilizadas
* **Java:** Linguagem de programação principal utilizada para implementar o sistema.
* **Exceção personalizada:** Uso de `ParametrosInvalidosException` para validação de negócios.
* **Lógica de Controle de Fluxo:** Utilização de `for` para realizar a contagem incremental.

### Como Executar
1. Clone o repositório para o seu ambiente local.
2. Compile o projeto em uma IDE Java como IntelliJ IDEA ou Eclipse.
3. Execute a classe `Contador.java`.
4. Insira dois números inteiros no terminal quando solicitado.
    * Se o segundo número for maior, o programa irá imprimir a contagem incremental.
    * Se o primeiro número for maior, o programa irá lançar a exceção customizada.


### Contribuições
Este projeto foi desenvolvido com fins educacionais, exercitando conceitos de controle de fluxo e exceções personalizadas em Java. Contribuições e melhorias são bem-vindas!