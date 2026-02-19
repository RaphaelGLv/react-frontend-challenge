# 🎬 CineDash - Frontend Challenge

Bem-vindo ao desafio técnico para a vaga de **Desenvolvedor React Pleno**.

O objetivo deste desafio é avaliar suas habilidades em arquitetura frontend, consumo de APIs complexas, gerenciamento de estado e boas práticas de UX/UI. Não buscamos apenas "código que funciona", mas sim **código que escala**.

## 🧠 O Desafio

Você deve construir o **CineDash**, um dashboard de curadoria e descoberta de filmes utilizando a [API do TMDB](https://developer.themoviedb.org/docs/getting-started).
Imagine que este é um produto interno usado por curadores de cinema para selecionar quais filmes entrarão no catálogo de um streaming.

### 🎯 Funcionalidades Obrigatórias (Core)

1.  **Autenticação (Simulada):**
    - Tela simples de login (apenas validação visual, sem backend real).
    - O usuário só acessa o dashboard autenticado.
2.  **Dashboard de Descoberta:**
    - Listagem de filmes (Trending/Popular) com paginação ou infinite scroll.
    - **Filtros Avançados:** Filtrar por Gênero, Ano de Lançamento e Nota Mínima (Rating).
3.  **Minha Lista (Watchlist):**
    - Adicionar/Remover filmes de uma lista de favoritos.
    - Esta lista deve persistir mesmo após o reload da página.
4.  **Detalhes do Filme:**
    - Rota dinâmica (`/movie/:id`) exibindo sinopse, elenco, nota e trailer (se houver).

## 🛠 Tech Stack Obrigatória

- **Core:** React 18+, TypeScript (Strict), Vite.
- **Server State & Cache:** TanStack Query.
- **Client State:** Zustand.
- **Routing:** TanStack Router (Preferencial) ou React Router v6 (com Data Loaders).
- **UI Components:** Shadcn/ui + TailwindCSS.
- **Formulários:** React Hook Form ou TanStack Form + Zod (validação).
- **Testes:** Vitest + React Testing Library.

> **Diferencial:** Implementação de `TanStack Table` para listagens complexas.

## 🏗 Requisitos de Arquitetura

Esperamos ver uma estrutura de projeto que suporte crescimento.

- **Feature-Sliced Design (FSD)** ou **Clean Architecture** adaptada ao Frontend.
- Isolamento de regras de negócio (hooks customizados vs componentes de UI).
- **Git Flow:** Utilize commits semânticos e organize seu trabalho em branches/PRs.

## 🎨 UI/UX

- Layout responsivo e fluido.
- Feedback visual para o usuário (Loadings, Skeletons, Toasts de erro/sucesso).
- Tema Dark/Light (persistido via Zustand).

## 📝 O que será avaliado?

1.  **Qualidade de Código:** Clareza, tipagem estrita (sem `any`), componentização.
2.  **Domínio das Ferramentas:** Uso eficiente de cache e seletores do Zustand.
3.  **Arquitetura:** Como você organiza pastas e arquivos pensando em escalabilidade?
4.  **Testes:** Testes unitários de hooks/funções e testes de integração de fluxos críticos.
5.  **Documentação:** Um arquivo explicando suas decisões técnicas e como rodar seu projeto.

## 🚀 Como entregar

1.  Crie um repositório privado e nos convide.
2.  Desenvolva sua solução em uma branch separada (ex: `feature/cinedash-impl`).
3.  Quando finalizar, abra um **Pull Request** para a branch `main` do seu repositório.
4.  Crie um arquivo `ARCHITECTURE.md` explicando suas decisões técnicas.
5.  Crie um arquivo `INSTRUCTIONS.md` explicando como rodar seu projeto.
6.  No corpo do PR, inclua uma breve descrição do que foi feito.
7.  Envie o link do repositório para o recrutador.

## 🔗 Recursos Úteis

- [Documentação TMDB](https://developer.themoviedb.org/docs)
- [TanStack Docs](https://tanstack.com/)
- [Feature-Sliced Design](https://feature-sliced.design/)

Boa sorte! Estamos ansiosos para ver sua solução. 🚀
