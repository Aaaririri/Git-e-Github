# Capacitação Git e Github

## O que é o Git?

Git é um sistema de controle de versões. O Git é utilizado, principalmente, para o trabalho em equipe. Através do Git, é possível notificar modificações feitas em um projeto para a equipe toda, comparar essas modificações e selecionar versões de um projeto conforme o mesmo é atualizado. Todas as versões e alterações ficam armazenadas. Versões idênticas não são salvas mais de uma vez, o que garante uma organização melhor do projeto. Sendo assim, que é armazenado no Git são os estados de um arquivo.
O criador do Git é Linus Torvalds, o mesmo criador do Linux.  

## Instalação


## O que é o Github?

O GitHub é uma plataforma de hospedagem de código-fonte e colaboração baseada na web. Ele permite que os desenvolvedores armazenem e gerenciem seus projetos de software usando o sistema de controle de versão Git. O GitHub fornece uma interface intuitiva e recursos poderosos para facilitar o trabalho colaborativo em equipes de desenvolvimento.

Ao usar o GitHub, os desenvolvedores podem criar repositórios para seus projetos, que são como pastas para armazenar e organizar o código-fonte. Esses repositórios podem ser públicos, permitindo que qualquer pessoa veja e contribua com o código, ou privados, acessíveis apenas para colaboradores autorizados.

Uma das principais vantagens do GitHub é a capacidade de rastrear as alterações feitas no código ao longo do tempo. Os desenvolvedores podem criar "commits" para registrar as modificações feitas em seus arquivos e ramos (branches) para trabalhar em diferentes versões do código simultaneamente. Além disso, o GitHub oferece recursos de "pull request", onde os desenvolvedores podem revisar e discutir as alterações antes de mesclá-las ao código principal.

O GitHub também possui recursos de gerenciamento de problemas (issues) que permitem aos desenvolvedores acompanhar e resolver bugs, solicitações de recursos e outras tarefas relacionadas ao projeto. Além disso, a plataforma oferece recursos para integração contínua (CI) e implantação contínua (CD), permitindo a automação de testes e implementações em diferentes ambientes.

O GitHub se tornou uma plataforma amplamente utilizada na comunidade de desenvolvimento de software, com milhões de desenvolvedores e organizações hospedando seus projetos na plataforma. Além disso, o GitHub fornece suporte para colaboração em equipe, facilitando a contribuição de vários desenvolvedores em um mesmo projeto.

## Configurando Acessos

### Token

### SSH

## Primeiro Respositório

### Via Github App

### Via Github Web

Para criar um repositório no Github:

1. Entre em sua conta na plataforma;

<p align="left">
    <img src="images/sign-in-github.png" tittle="Sign In no Github" height="250">
</p>

2. No canto superior direito, busque o ícone de "+" e selecione "Novo repositório";

<p align="left">
    <img src="images/repo-create.png" tittle="New Repositório" height="250">
</p>

3. Digite um nome de repositório e se desejar pode adicionar uma breve descrição no campo "Descrição";

<p align="left">
    <img src="images/create-repository-name.png" tittle="New Repositório" height="100">
</p>

4. Escolha se deseja que seu repositório seja público ou privado, se quer inicializar o projeto com um README.MD e clique em "Criar Repositório".

### Via Terminal

## Comandos Básicos

## Conventional Commits

A convenção dos Conventional Commits consiste em seguir um formato específico para a mensagem de commit, que geralmente é composta por três partes principais: tipo, escopo e descrição. A estrutura básica da mensagem de commit é a seguinte:

```
<tipo>(<escopo>): <descrição>
```

1. `Tipo`: Indica a natureza da alteração realizada. Pode ser um dos seguintes valores:

    - `feat`: Adição de uma nova funcionalidade.
    - `fix`: Correção de um bug.
    - `docs`: Alterações na documentação.
    - `style`: Alterações na formatação do código, como espaçamento, indentação, etc.
    - `refactor`: Refatoração do código, sem adição de novas funcionalidades ou correção de bugs.
    - `test`: Adição ou modificação de testes.
    - `chore`: Atualizações diversas, como alterações em scripts de build, configurações, etc.
  
2. `Escopo` (opcional): Indica a parte específica do projeto que foi modificada. Pode ser uma funcionalidade, um componente, um módulo, etc.

3. `Descrição`: Uma breve descrição da alteração realizada, usando verbos no imperativo. Deve ser clara e objetiva.    

## Maneiras de contribuir com o Open Source
[Como Contribuir para o Open Source](https://opensource.guide/pt/how-to-contribute/)

## Referências

- [ChatGPT](https://chat.openai.com)
- [Getting Started Installing Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- [Uma breve história do Git](https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-Uma-Breve-Hist%C3%B3ria-do-Git)
- [Criar um repositório](https://docs.github.com/pt/get-started/quickstart/create-a-repo)
- [Criando um token de acesso pessoal](https://docs.github.com/pt/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)
- [Conectar-se ao GitHub com o SSH](https://docs.github.com/pt/authentication/connecting-to-github-with-ssh)
- [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)
- [Conventional Commits Pattern](https://medium.com/linkapi-solutions/conventional-commits-pattern-3778d1a1e657)
