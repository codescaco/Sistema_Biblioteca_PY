# Sistema_Biblioteca_PY
Sistema simples para uma biblioteca em Python (Projeto Integrado Anhanguera)

# Sistema de Gerenciamento de Biblioteca

Este é um programa simples em Python orientado a objetos para gerenciar uma biblioteca. O sistema permite o cadastro de livros e usuários, bem como o gerenciamento de empréstimos e devoluções.

## Funcionalidades

- Cadastro de Livros
- Cadastro de Usuários
- Empréstimo de Livros
- Devolução de Livros
- Consulta de Livros
- Geração de Relatórios

## Requisitos

- Python 3.x

## Como Executar

1. Clone este repositório ou baixe o arquivo fonte.

2. Navegue até o diretório onde o arquivo foi salvo.

3. Execute o programa com o seguinte comando:

    ```bash
    python biblioteca.py
    ```

## Instruções de Uso

Após executar o programa, você verá um menu com várias opções. Você pode selecionar a opção desejada digitando o número correspondente e pressionando Enter.

### Menu de Opções

1. **Cadastrar Livro**
    - ID do Livro: Identificador único do livro (inteiro).
    - Título: Título do livro.
    - Autor: Autor do livro.
    - Ano de Publicação: Ano em que o livro foi publicado (inteiro).
    - Número de Cópias: Quantidade de cópias disponíveis na biblioteca (inteiro).

2. **Cadastrar Usuário**
    - ID do Usuário: Identificador único do usuário (inteiro).
    - Nome: Nome do usuário.
    - Número de Identificação: Número de identificação do usuário.
    - Contato: Informação de contato do usuário.

3. **Emprestar Livro**
    - ID do Usuário: Identificador do usuário que está emprestando o livro (inteiro).
    - ID do Livro: Identificador do livro que está sendo emprestado (inteiro).

4. **Devolver Livro**
    - ID do Usuário: Identificador do usuário que está devolvendo o livro (inteiro).
    - ID do Livro: Identificador do livro que está sendo devolvido (inteiro).

5. **Consultar Livros**
    - Título (opcional): Título do livro para busca (pode ser parcial).
    - Autor (opcional): Nome do autor para busca (pode ser parcial).
    - Ano de Publicação (opcional): Ano de publicação para busca (inteiro).

6. **Gerar Relatório**
    - Gera um relatório com a lista de livros disponíveis, usuários cadastrados e empréstimos realizados.

7. **Sair**
    - Encerra o programa.

## Exemplo de Uso

### Cadastrando um Livro

1. Selecione a opção "1" no menu principal.
2. Insira o ID do Livro, Título, Autor, Ano de Publicação e Número de Cópias quando solicitado.

### Cadastrando um Usuário

1. Selecione a opção "2" no menu principal.
2. Insira o ID do Usuário, Nome, Número de Identificação e Contato quando solicitado.

### Emprestando um Livro

1. Selecione a opção "3" no menu principal.
2. Insira o ID do Usuário e o ID do Livro quando solicitado.

### Devolvendo um Livro

1. Selecione a opção "4" no menu principal.
2. Insira o ID do Usuário e o ID do Livro quando solicitado.

### Consultando Livros

1. Selecione a opção "5" no menu principal.
2. Insira os critérios de busca desejados (Título, Autor, Ano de Publicação). Você pode deixar os campos em branco para ignorá-los.

### Gerando Relatório

1. Selecione a opção "6" no menu principal.
2. O relatório será exibido no console.

### Saindo do Programa

1. Selecione a opção "7" no menu principal.
