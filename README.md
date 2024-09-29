# Tarefa Engenharia Git

Este repositório foi criado como parte da disciplina de Engenharia de Software. O objetivo é demonstrar o uso do Git para controle de versão, incluindo a criação de repositórios, branches, gerenciamento de Pull Requests, e resolução de conflitos.

## Descrição do Projeto

O projeto consiste em uma simples aplicação Python que imprime "Hello World" no console. Além disso, o repositório serve como uma prática para a utilização do Git e GitHub em projetos colaborativos.

## Estrutura do Projeto

- **README.md**: Este arquivo, que contém informações sobre o projeto.
- **main.py**: Um arquivo Python que contém o código para imprimir "Hello World".

## Como Usar

Para executar o projeto, siga os passos abaixo:

1. Clone o repositório:

   ```bash
   git clone https://github.com/Pedro-Estevao/tarefa-engenharia-git.git

2. Navegue até o repositório do projeto: 

    ```bash
    cd tarefa-engenharia-git

3. Execute o arquivo Python:

    ```bash
    python main.py

## Comandos Git Utilizados

A seguir listo a ordem dos comandos Git utilizados no desenvolvimento deste projeto:

1. Criação do repositório local

    ```bash
    mkdir tarefa-engenharia-git && cd .\tarefa-engenharia-git\

2. Inicialização do Git no repositório

    ```bash
    git init

3. Após repositório remoto criado no GitHub. Conexão com o local

    ```bash
    git remote add origin https://github.com/Pedro-Estevao/tarefa-engenharia-git.git

4. Adição do `README.md` criado ao Git

    ```bash
    git add README.md

5. Commit da alteração

    ```bash
    git commit -m "Adição do README.md informando sobre o projeto"

6. Envio das alterações locais para o repositório remoto

    ```bash
    git push origin main

7. Criação e mudança para branch `desenvolvimento`

    ```bash
    git checkout -b desenvolvimento

8. Adição do `main.py` criado ao Git

    ```bash
    git add main.py

9. Commit da alteração

    ```bash
    git commit -m "Adição do main.py criado"

10. Envio das alterações locais para o repositório remoto

    ```bash
    git push origin desenvolvimento

11. Após realizado o Pull Request. Mudança para a branch `main`

    ```bash
    git checkout main
    git pull origin main

12. Alterado o arquivo `README.md` na branch `main`. Adicionar ao Git e commitar

    ```bash
    git add README.md
    git commit -m "Modificação no README.md da branch main"

13. Mudança para a branch `desenvolvimento`

    ```bash
    git checkout desenvolvimento
    git pull origin desenvolvimento

14. Alterado o arquivo `README.md` na brach `desenvolvimento`. Adicionar ao Git e commitar

    ```bash
    git add README.md
    git commit -m "Modificação no README.md da branch desenvolvimento"

15. Mudança para a branch `main`

    ```bash
    git checkout main

16. Tentativa de realização do merge da branch `desenvolvimento` para `main`

    ```bash
    git merge desenvolvimento

17. Resolvidos os conflitos. Adição e commit do arquivo

    ```bash
    git add README.md
    git commit -m "Correção dos conflitos no README.md"

18. Envio das alterações para o repositório remoto

    ```bash
    git push origin main

19. Listagem dos logs

    ```bash
    git log

20. Escolhido um commit, o revertemos

    ```bash
    git revert <id-do-commit>