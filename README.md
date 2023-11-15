# Spring Teste Java

Este repositório contém um exemplo simples de aplicação Java usando o framework Spring.

## Descrição

O projeto apresenta um aplicativo básico que demonstra o uso do Spring Boot para criar um serviço web simples.

## Pré-requisitos

Certifique-se de ter o seguinte instalado em sua máquina local:

- Java Development Kit (JDK) 17 ou superior
- Gradle para construir o projeto

## Configuração

1. Clone este repositório: `git clone https://github.com/seu-usuario/spring-teste-java.git`
2. Navegue até o diretório do projeto: `cd spring-teste-java`

## Executando a aplicação

Para executar a aplicação, use o seguinte comando Gradle:

```./gradlew bootRun```


Isso iniciará o servidor embutido do Spring Boot e a aplicação estará acessível em `http://localhost:8080`.

## Rotas

- `/hello`: Rota para testar a funcionalidade básica do aplicativo. Você pode passar um parâmetro `name` opcional na URL para cumprimentar alguém específico.

Exemplo de uso:

`http://localhost:8080/hello?name=Spring`


Isso retornará uma mensagem "Hello Spring!".

## Estrutura do Projeto

- `src/`: Contém o código-fonte da aplicação
    - `main/`: Código-fonte principal da aplicação
        - `java/com/example/demo/`: Pacote principal da aplicação
            - `DemoApplication.java`: Arquivo principal da aplicação Spring Boot
    - `test/`: Código de teste
        - `java/com/example/demo/`: Pacote de testes da aplicação

## Autor

[Isabela Baséggio](https://github.com/IsabelaBaseggio/)

## Licença

Este projeto está licenciado sob a [Licença MIT](https://opensource.org/licenses/MIT) - veja o arquivo [LICENSE](https://github.com/IsabelaBaseggio/spring-java-teste/blob/main/LICENSE) para mais detalhes.
