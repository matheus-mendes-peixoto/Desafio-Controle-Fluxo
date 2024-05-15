# Contador

Este é um simples programa em Java para contar de forma ascendente a partir de um parâmetro inicial até um segundo parâmetro, ambos fornecidos pelo usuário. Ele também apresenta uma verificação para garantir que o segundo parâmetro seja maior que o primeiro.

## Requisitos

- Java Development Kit (JDK) instalado no seu sistema.

## Como executar

1. Clone este repositório para o seu ambiente local:

- [git clone](https://github.com/matheus-mendes-peixoto/Desafio-Controle-Fluxo).


2. Navegue até o diretório onde o código está localizado:

- cd seu-repositorio

3. Compile o programa usando o comando:

- javac Contador.java

4. Execute o programa com o comando:

- java Contador


5. Siga as instruções no terminal para inserir os parâmetros.

## Funcionamento

- O programa solicita que o usuário forneça dois parâmetros inteiros.
- Em seguida, verifica se o segundo parâmetro é maior que o primeiro.
- Se o segundo parâmetro for maior, o programa conta de forma ascendente a partir do primeiro parâmetro até o segundo, imprimindo cada número no console.
- Se o segundo parâmetro não for maior que o primeiro, uma exceção é lançada e uma mensagem é exibida no console.

## Estrutura do Código

- O código principal está contido na classe `Contador`.
- O método `main` recebe os parâmetros do usuário e chama o método `contar`.
- O método `contar` verifica se o segundo parâmetro é maior que o primeiro e, em seguida, executa a contagem.
- Se os parâmetros forem inválidos, uma exceção `ParametrosInvalidosException` é lançada.

## Contribuindo

- Sinta-se à vontade para contribuir com melhorias ou correções.
- Abra um problema (issue) se encontrar algum bug ou desejar propor uma nova funcionalidade.
