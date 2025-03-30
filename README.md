# To-Do List - Trabalho de Desenvolvimento de Software em Nuvem

Este projeto é um **CRUD simples de To-Do List** desenvolvido como parte do trabalho da disciplina de **Desenvolvimento de Software em Nuvem** do curso de **Análise e Desenvolvimento de Sistemas (ADC)** na **Unifor**.

## Descrição

O sistema consiste em uma lista de tarefas (To-Do List) que permite realizar as operações de **criar**, **ler**, **atualizar** e **excluir** tarefas. Foi desenvolvido utilizando **JavaScript** para o front-end e **Node.js** para o back-end, com **Back4App** como banco de dados para armazenar as tarefas.

## Tecnologias Utilizadas

- **Front-End**:
  - **HTML**: Estrutura da página.
  - **CSS**: Estilização simples da página.
  - **JavaScript**: Lógica para manipulação das tarefas e integração com o back-end.

- **Back-End**:
  - **Node.js**: Framework para criar o servidor e manipular as requisições.
  - **Back4App**: Banco de dados utilizado para persistir as tarefas (usando o Parse Server).

## Funcionalidades

- **Adicionar tarefa**: O usuário pode inserir uma nova tarefa com título, descrição, status e data de vencimento.
- **Visualizar tarefas**: O sistema exibe todas as tarefas cadastradas.
- **Editar tarefa**: O usuário pode editar uma tarefa existente, alterando o título, descrição, status ou data de vencimento.
- **Excluir tarefa**: O usuário pode excluir uma tarefa da lista.

## Como Rodar o Projeto

1. Clone este repositório para sua máquina local:
    ```bash
    git clone https://github.com/usuario/repositorio.git
    ```

2. Abra o diretório do projeto no terminal.

3. Instale as dependências do Node.js:
    ```bash
    npm install
    ```

4. Certifique-se de configurar as variáveis de ambiente necessárias, como o **APP_ID** e **JAVASCRIPT_KEY** do Back4App.

5. Inicie o servidor:
    ```bash
    node index.js
    ```

6. Acesse o front-end em seu navegador no endereço:
    ```
    http://localhost:5000
    ```

## Observações

- Este projeto foi desenvolvido por **3 alunos**:  
  - **Paulo Vitor Temoteo Araújo (2326178)**  
  - **Antonia Taynara Maciel Paulo (2323818)**  
  - **Francisca Josiana dos Santos Oliveira (2323835)**

- **Versionamento**: O projeto não foi versionado adequadamente, pois apenas um dos membros do grupo tem acesso a um computador neste momento. Em futuras versões, o versionamento será implementado corretamente.

## Licença

Este projeto é de domínio aberto para fins educacionais.

---

**Trabalho de ADC - Desenvolvimento de Software em Nuvem - Unifor**
