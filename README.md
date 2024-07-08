# Basic MVC - Exemplo de Aplicação MVC em Java

Este repositório contém um exemplo básico de uma aplicação MVC (Model-View-Controller) em Java.

## Estrutura do Projeto

O projeto está estruturado da seguinte forma:

- `src/`: Contém os arquivos da aplicação.
    - `controller/`: Controladores da aplicação.
        - `BasicController.java`: Controlador básico para manipulação de dados.
        - `BasicControllerGeneric.java`: Controlador genérico para operações comuns.
    - `model/`: Modelos de dados da aplicação.
        - `AbstractModel.java`: Classe abstrata para os modelos.
        - `Account.java`, `Address.java`, `Business.java`, `Card.java`, `Person.java`, `Phone.java`: Modelos específicos
          de entidades.
    - `repository/`: Classes responsáveis pelo acesso aos dados.
        - `BasicRepository.java`: Repositório básico para operações de persistência.
        - `BasicRepositoryGeneric.java`: Repositório genérico para operações comuns de persistência.
    - `service/`: Serviços que implementam a lógica de negócios.
        - `BasicService.java`: Serviço básico para regras de negócio específicas.
        - `BasicServiceGeneric.java`: Serviço genérico para lógicas comuns de serviço.
    - `Main.java`: Classe principal que inicia a aplicação.

## Configuração do Ambiente

Para configurar o ambiente de desenvolvimento:

1. Clone este repositório:
   ```bash
   git clone https://github.com/rodolfod2r2/Basic-MVC.git
2. Abra o projeto em seu IDE preferido (Eclipse, IntelliJ, etc.).
3. Certifique-se de ter o JDK (Java Development Kit) instalado e configurado corretamente.

## Uso

### Execução

Para executar a aplicação, você pode seguir estes passos:
Compile os arquivos Java:

    ```bash
    javac src/*.java src/controller/*.java src/model/*.java src/repository/*.java src/service/*.java

Execute a classe principal para iniciar a aplicação:

    ```bash
    java src/Main

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests para melhorias no código,
documentação ou qualquer outra sugestão que possa beneficiar o projeto.