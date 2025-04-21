# Restaurante do Veneno - Sistema de Informação

Este é um sistema simples para cadastro e gerenciamento de produtos de um restaurante. O projeto utiliza HTML, JavaScript e Bootstrap para criar uma interface amigável e responsiva.

## Estrutura do Projeto

O projeto possui os seguintes arquivos:

- **[index.html](index.html)**: Página inicial com um link para a página de cadastro de produtos.
- **[cadastrar.html](cadastrar.html)**: Página para cadastro e gerenciamento de produtos.
- **[package.json](package.json)**: Arquivo de configuração do projeto, contendo a dependência do Bootstrap.
- **[.hintrc](.hintrc)**: Arquivo de configuração para o validador de código HTMLHint.

## Funcionalidades

### Página Inicial (`index.html`)
- Contém um link para a página de cadastro de produtos.

### Página de Cadastro (`cadastrar.html`)
- Permite cadastrar produtos com os seguintes campos:
  - Nome do produto (obrigatório, mínimo de 3 caracteres).
  - Preço do produto (obrigatório, maior que 0).
  - Descrição do produto (opcional).
- Exibe uma tabela com os produtos cadastrados.
- Possui validação de campos com mensagens de erro.
- Permite limpar o formulário após o cadastro.
- Exibe uma mensagem de sucesso ao cadastrar um produto.

## Dependências

O projeto utiliza o Bootstrap(local) para estilização. A dependência está especificada no arquivo `package.json`:

```json
{
  "dependencies": {
    "bootstrap": "^5.3.5"
  }
}