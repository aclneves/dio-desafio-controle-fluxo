# Desafio Controle de Fluxo - DIO

Este projeto é uma solução para o Desafio de Controle de Fluxo, parte do bootcamp de Java da [Digital Innovation One](https://www.dio.me/). O objetivo é criar um programa que recebe dois números inteiros como parâmetros, valida-os e, em seguida, imprime no console uma contagem baseada na diferença entre eles.

## 📜 Descrição

O programa solicita ao utilizador que insira dois números inteiros. A lógica principal do programa é a seguinte:
1.  Verifica se o segundo número é maior que o primeiro. Se não for, lança uma exceção personalizada (`ParametrosInvalidosException`).
2.  Calcula a diferença entre os dois números.
3.  Utiliza um laço `for` para imprimir no console os números de 1 até a diferença calculada.
4.  Realiza o tratamento adequado para as exceções de negócio e de entrada de dados.

## ✨ Funcionalidades

*   Leitura de dois parâmetros numéricos via terminal.
*   Validação para garantir que o segundo parâmetro é maior que o primeiro.
*   Uso de uma exceção personalizada para lidar com regras de negócio.
*   Laço de repetição `for` para iterar e imprimir a contagem.

## 🛠️ Tecnologias Utilizadas

*   **Java 24:** O projeto foi desenvolvido utilizando a versão 24 do Java SDK.
*   **IntelliJ IDEA:** IDE utilizada para o desenvolvimento.

## 🚀 Como Executar o Projeto

1.  **Pré-requisitos:**
    *   Ter o Java JDK 24 (ou superior) instalado e configurado no seu sistema.

2.  **Clone o repositório:**
    ```bash
    git clone <URL-DO-SEU-REPOSITORIO>
    ```

3.  **Navegue até o diretório do projeto:**
    ```bash
    cd <NOME-DO-SEU-DIRETORIO>
    ```

4.  **Compile o código:**
    Navegue até o diretório onde se encontra o ficheiro `Contador.java` e execute o seguinte comando para compilar:
    ```bash
    javac Contador.java
    ```
    (Nota: Se a sua estrutura de pacotes for `br.com.dio.exceptions`, certifique-se de compilar a partir do diretório raiz do `src`).

5.  **Execute o programa:**
    Após a compilação, execute o seguinte comando:
    ```bash
    java Contador
    ```

6.  **Interaja com o programa:**
    O terminal solicitará que insira o primeiro e o segundo parâmetro.
    ```
    Digite o primeiro parâmetro:
    5
    Digite o segundo parâmetro:
    15
    ```

    O resultado será a impressão dos números de 1 a 10.
    ```
    Imprimindo o número 1
    Imprimindo o número 2
    ...
    Imprimindo o número 10
    ```