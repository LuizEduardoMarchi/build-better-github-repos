<p align="center">
  <img src="banner-build-better-github-repos.png" alt="Build Better GitHub Repos">
</p>

# 📝 Construa melhores repositórios no GitHub em 2026

[![English](https://img.shields.io/badge/lang-en-blue)](README.md)

![GitHub repo size](https://img.shields.io/github/repo-size/LuizEduardoMarchi/build-better-github-repos)
![GitHub stars](https://img.shields.io/github/stars/LuizEduardoMarchi/build-better-github-repos)
![GitHub forks](https://img.shields.io/github/forks/LuizEduardoMarchi/build-better-github-repos)
![GitHub last commit](https://img.shields.io/github/last-commit/LuizEduardoMarchi/build-better-github-repos)
![License](https://img.shields.io/badge/license-MIT-green)

# 📝 Guia de construção de repositórios no GitHub

        💡 Em pleno 2026, muitas pessoas ainda têm dúvidas sobre como organizar bem um repositório no GitHub. Ter um projeto funcional é importante, mas apresentá-lo de forma clara e organizada pode fazer toda a diferença para quem visita seu perfil.

        📖 Pensando nisso, criei este pequeno guia com algumas boas práticas que podem ajudar você a estruturar melhor seus repositórios. Seguindo essas dicas, seus projetos ficarão mais organizados, profissionais e muito mais fáceis de entender para qualquer pessoa que acessar o seu perfil.

> **🔥Dica:** escolha bons nomes para seus projetos. Um nome claro e chamativo pode despertar a curiosidade de quem visita seu perfil pela primeira vez.
Lembre-se: a primeira impressão é a que fica.

**👋 Olá! Meu nome é Luiz Eduardo, sou estudante de Engenharia de Software e utilizo este perfil para publicar projetos acadêmicos e projetos pessoais, como este guia.**

        ✨ O objetivo deste repositório é ajudar outras pessoas a organizarem melhor seus projetos no GitHub, incentivando boas práticas de documentação, organização e apresentação de código.


## 📚 Sumário

- 📌 [Sobre o projeto](#-sobre-o-projeto)
- 📖 [O que é um README](#-antes-de-tudo-o-que-é-um-arquivo-readme)
- ⏳ [Antes X Depois](#antes-x-depois-de-um-readme)
- 🏗️ [Estrutura do repositório](#️-como-construir-a-estrutura-do-seu-repositório)
- 🏷️ [Nome do projeto](#️-1--nome-do-projeto)
- 📝 [Descrição do projeto](#-2--descrição-do-projeto)
- ⚙️ [Funcionalidades](#️-3--funcionalidades)
- 🧰 [Tecnologias](#-4--tecnologias-utilizadas)
- 📁 [Estrutura do projeto](#-5--estrutura-do-projeto)
- 🧪 [Como executar](#-6--como-executar-o-projeto)
- ⚙️ [Como funciona](#️-7--como-o-sistema-funciona)
- 🤝 [Contribuições](#-8--contribuições)
- 📊 [Status](#-9--status-do-projeto)
- 📜 [Licença](#-10--licença)
- 👤 [Autor](#-11--autor)
- 🏁 [Conclusão](#-conclusão)
- 📌 [Ícones para README](#-ícones-para-utilizar-em-seu-readme)



## 📌 Sobre o projeto

Este repositório apresenta um guia prático de boas práticas para organização de projetos no GitHub.

## 📖 Antes de tudo, o que é um arquivo README?

> 📌 O arquivo README funciona como a vitrine do seu projeto.
É nele que qualquer visitante terá o primeiro contato com o seu trabalho e entenderá rapidamente do que se trata o repositório.

### Antes X Depois de um README

        ❌ README ruim

            • Título
            • Descrição
            • Como executar

        ✅ README estruturado

            • Título
            • Descrição
            • Sumário
            • Funcionalidades
            • Tecnologias
            • Estrutura
            • Execução
            • Funcionamento
            • Guia
            • Contribuições
            • Licença
            • Autor

### Regra das 5 perguntas
    1- O que é este projeto?
    2- O que ele faz?
    3- Como executar o projeto?
    4- Como o código foi estruturado?
    5- Como alguém pode contribuir com o projeto?
---
> 🧭 *Se o seu **README** responder claramente a essas cinco perguntas, ele já estará cumprindo muito bem o seu papel.*

### 🚀 Agora vamos ao que realmente importa

## 🏗️ Como construir a estrutura do seu repositório?

        No livro The Pragmatic Programmer, os autores apresentam uma ideia muito importante sobre o desenvolvimento de software:

        “Programação é mais do que apenas escrever código. Bons desenvolvedores pensam sobre o problema, o design e a organização do sistema antes mesmo de começar a implementar.”

        Isso significa que organização e planejamento também fazem parte do processo de desenvolvimento.

#### **🔗 Referência: Hunt, Andrew; Thomas, David. The Pragmatic Programmer. Addison-Wesley.**

* ⚠️ Importante: o objetivo deste guia é ajudar a organizar e melhorar a página de um repositório do zero ou já existente, e não ensinar como desenvolver um **projeto** do zero.


### 📂 Estrutura recomendada para um repositório

## 🏷️ 1 — Nome do projeto

        Este é o primeiro contato que o usuário terá com o seu projeto, portanto deve ser claro, intuitivo e fácil de lembrar.

        Uma boa prática é utilizar nomes simples em minúsculo e separados por hífen, padrão conhecido como kebab-case, muito utilizado pela comunidade de desenvolvimento.

> Exemplo:
> - software-engineering-projects

## 📝 2 — Descrição do projeto

        Apresente uma explicação breve sobre o que é o projeto e qual problema ele resolve.

> Exemplo:
> - Repositório destinado à publicação de arquivos e atividades realizadas durante a graduação em Engenharia de Software.

## ⚙️ 3 — Funcionalidades

        Liste as funcionalidades disponíveis no projeto.
        
        Também é possível mencionar funcionalidades que ainda serão implementadas futuramente.

> Exemplo:
> - Cadastro de usuários
> - Criação de reservas
> - Listagem de reservas
> - Integração com banco de dados (em desenvolvimento)

## 🧰 4 — Tecnologias utilizadas

        Essa seção ajuda o visitante a entender rapidamente quais ferramentas foram utilizadas no desenvolvimento do projeto.
> Exemplo:
> - C++
> - Git
> - PostgreSQL

## 📁 5 — Estrutura do projeto

        Aqui você pode mostrar como o projeto está organizado internamente.

        Isso ajuda outros desenvolvedores a entenderem rapidamente a arquitetura do código.

```
Exemplo:

sistema-autenticacao/
├── src/
│   ├── main.cpp
│   └── utils.cpp
├── docs/
│   └── guia-autenticacao.md
├── modules/
│   └── autenticacao/
│       └── autenticacao.cpp
├── database/
│   └── database.cpp
├── config/
│   └── config.cpp
└── tests/
    └── test_main.cpp
```

## 🧪 6 — Como executar o projeto
        Explique de forma simples como qualquer pessoa pode executar o projeto.
    Também é importante informar a versão da linguagem utilizada.

```
Exemplo utilizando C++

Para compilar e executar este projeto, você precisará de:

- Linguagem: C++ (padrão C++20)
- Compilador: GCC 10+, Clang 10+ ou MSVC 19.28+
```
> Para executar o projeto no terminal: 
> - git clone <link_do_repositorio>
> - g++ main.cpp -o login
> - ./login

## ⚙️ 7 — Como o sistema funciona

        Nesta seção você pode explicar brevemente o funcionamento geral do sistema.
 
> Exemplo
> - O sistema funciona por meio do terminal, onde o usuário pode realizar autenticação e configurar seu perfil.

## 🤝 8 — Contribuições

        Se o projeto for aberto a contribuições, explique como outras pessoas podem participar.

```
Exemplo

> - Contribuições são bem-vindas.
> - Sinta-se à vontade para abrir issues ou enviar pull requests.

>  Também é possível reconhecer pessoas que contribuíram para o projeto:
> - [Nome do colega] — lógica da IA.
> - [Seu nome] — estrutura do projeto e C++.
> - [Outro colaborador] — documentação e testes.
```

## 📊 9 — Status do projeto

        Informe em qual estágio o projeto se encontra.

```
Exemplo:

> 🚧 Em desenvolvimento
             ou
>      ✅ Concluído
```
## 📜 10 — Licença

        Aqui você define como outras pessoas podem utilizar seu projeto.

> Exemplo
> - Este projeto está sob a licença MIT.

## 👤 11 — Autor

        Inclua seu nome caso seja o autor principal do projeto.

> Exemplo
> - Luiz Eduardo Marchi

<hr style="height:4px;border:none;background-color:gray;">

## ⭐ Se este guia foi útil

Se este guia ajudou você de alguma forma, considere deixar uma ⭐ no repositório.
Isso ajuda outras pessoas a encontrarem o projeto.

## 🏁 Conclusão

        💡 Organizar bem um repositório pode parecer algo simples, mas faz uma grande diferença na forma como seu trabalho é percebido por outras pessoas.

        Um projeto bem documentado demonstra organização, cuidado com detalhes e preocupação com boas práticas de desenvolvimento. Além disso, facilita a compreensão do código, incentiva contribuições e torna seu portfólio muito mais profissional.

        Se você aplicar essas pequenas melhorias aos seus repositórios, seus projetos não apenas ficarão mais fáceis de entender, como também passarão uma imagem muito mais sólida do seu trabalho como desenvolvedor.

        🧠 Lembre-se: não basta apenas escrever código — saber apresentar e documentar seu projeto também é uma habilidade importante na carreira de qualquer programador.

Abaixo estão alguns ícones úteis que podem ser utilizados para organizar seções em um README.

## 🎨 Ícones para utilizar em seu README

Os ícones podem ajudar a tornar a documentação mais visual e organizada.  
Abaixo estão alguns exemplos comuns utilizados em arquivos README.

### 📚 Estrutura geral

| Ícone | Uso comum | Exemplo |
|------|------|------|
| 📌 | Sobre o projeto | `## 📌 Sobre o projeto` |
| 📚 | Sumário | `## 📚 Sumário` |
| 📖 | Documentação | `## 📖 Documentação` |
| 🧠 | Conceitos ou explicações | `## 🧠 Conceitos` |

### ⚙️ Desenvolvimento

| Ícone | Uso comum | Exemplo |
|------|------|------|
| ⚙️ | Funcionamento do sistema | `## ⚙️ Como funciona` |
| 🧰 | Tecnologias utilizadas | `## 🧰 Tecnologias` |
| 🏗️ | Estrutura do projeto | `## 🏗️ Estrutura do projeto` |
| 🧪 | Testes | `## 🧪 Testes` |

### 🚀 Execução do projeto

| Ícone | Uso comum | Exemplo |
|------|------|------|
| 🚀 | Execução do projeto | `## 🚀 Como executar` |
| 💻 | Uso no terminal | `## 💻 Uso` |
| 📦 | Instalação | `## 📦 Instalação` |

### 🤝 Colaboração

| Ícone | Uso comum | Exemplo |
|------|------|------|
| 🤝 | Contribuições | `## 🤝 Contribuições` |
| 👥 | Colaboradores | `## 👥 Colaboradores` |
| 🐛 | Reportar bugs | `## 🐛 Bugs` |

### 📊 Informações do projeto

| Ícone | Uso comum | Exemplo |
|------|------|------|
| 📊 | Status do projeto | `## 📊 Status` |
| 📜 | Licença | `## 📜 Licença` |
| 👤 | Autor | `## 👤 Autor` |
| 🏁 | Conclusão | `## 🏁 Conclusão` |