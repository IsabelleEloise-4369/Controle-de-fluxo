# DesafioControleFluxo
Este projeto é uma solução para o desafio de controle de fluxo, onde um sistema recebe dois parâmetros via terminal, realiza validações e imprime uma sequência de números com base na diferença entre os parâmetros. Caso o primeiro parâmetro seja maior que o segundo, o sistema lança uma exceção personalizada.

## Estrutura do Projeto
O projeto contém as seguintes classes:

### Contador.java: Classe principal que executa o programa, recebe os parâmetros, chama o método de contagem e lida com a exceção.
### ParametrosInvalidosException.java: Exceção personalizada que é lançada quando o primeiro parâmetro é maior que o segundo.

## Funcionalidade
O sistema realiza as seguintes etapas:

- O programa solicita ao usuário dois parâmetros inteiros via terminal.
- Se o primeiro parâmetro for maior que o segundo, uma exceção personalizada (ParametrosInvalidosException) é lançada com a mensagem: "O segundo parâmetro deve ser maior que o primeiro".
- Se os parâmetros forem válidos (o primeiro é menor que o segundo), o sistema calcula a diferença entre eles e imprime no console uma sequência de mensagens, indicando o número de iterações realizadas.
