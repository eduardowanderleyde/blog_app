# Blog App

Este README documenta os passos necessários para executar e configurar o aplicativo Blog.

https://github.com/eduardowanderleyde/blog_app/assets/103546791/a646f6d4-b3d0-44bb-9d10-ee1805746f51

## Versão do Ruby

O aplicativo foi desenvolvido utilizando Ruby 3.0.0.

## Dependências do Sistema

Antes de executar o aplicativo, certifique-se de ter as seguintes dependências instaladas:

- Ruby 3.0.0
- PostgreSQL (ou outro banco de dados compatível)
- Node.js
- Yarn (opcionalmente para gerenciamento de pacotes JavaScript)

## Configuração

1. Clone este repositório:

    ```
    git clone https://github.com/eduardowanderleyde/blog_app.git
    ```

2. Instale as dependências do Ruby:

    ```
    bundle install
    ```

3. Instale as dependências do JavaScript (se estiver usando Yarn):

    ```
    yarn install
    ```

## Criação do Banco de Dados

Para configurar o banco de dados:

1. Copie o arquivo de configuração de banco de dados de exemplo:

    ```
    cp config/database.yml.example config/database.yml
    ```

2. Edite `config/database.yml` conforme necessário para configurar seu banco de dados.

3. Crie o banco de dados e execute as migrações:

    ```
    rails db:create
    rails db:migrate
    ```

## Inicialização do Banco de Dados

Se precisar inicializar o banco de dados com dados iniciais, execute:

